pipeline
{
  agent any
  stages
  {
    stage("clone")
    {
      steps
      {
        git 'https://github.com/Sarala3289/Helloworld.git'
      }
    }
    stage('build')
    {
      steps
      {
        sh 'javac Helloworld.java'
      }
    }
    stage('run')
    {
      steps
      {
        sh 'java Helloworld'
      }
    }
  }
}
    
