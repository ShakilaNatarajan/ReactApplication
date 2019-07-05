pipeline {
  agent any
  stages {
    stage('Coverage') {
      steps {
        bat 'npm run test:coverage'
      }
    }
  }
  tools {
    nodejs 'node'
  }
}