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
        echo 'test message'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}