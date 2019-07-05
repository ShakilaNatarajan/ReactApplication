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
        sh 'npm test -- --coverage'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}