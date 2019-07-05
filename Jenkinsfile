pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        bat 'npm install'
      }
    }
    stage('Coverage') {
      steps {
        bat 'npm test -- --coverage'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}