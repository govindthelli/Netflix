pipeline {
  agent any
  stages{
    stage('build'){
      steps{
        sh 'docker build .'
      }
    }
    stage('run'){
      steps{
        sh 'docker run -p 8000:8000'
      }
    }
  }
}
