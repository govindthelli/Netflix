pipeline {
  agent any
  stages{
    stage('build'){
      steps{
        sh 'docker build -t test .'
      }
    }
    stage('run'){
      steps{
        sh 'docker run --name demo -dp 8000:8000 test'
      }
    }
  }
}
