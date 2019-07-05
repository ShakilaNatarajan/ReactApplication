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
        bat 'npm react-scripts test --env=jsdom --coverage'
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