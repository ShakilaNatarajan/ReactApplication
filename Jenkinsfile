pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        sh 'npm install'
      }
    }
    stage('Coverage') {
      steps {
        sh 'npm test'
      }
    }
  }
  tools {
    nodejs 'node'
  }
  environment {
    PATH = 'C:\\Program Files\\Git\\usr\\bin'
  }
}