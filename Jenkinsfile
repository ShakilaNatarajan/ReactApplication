pipeline {
  agent any
  stages {
    stage('Coverage') {
      steps {
        bat 'npm test'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}