pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        bat 'npm install'
      }
    }
    stage('Jest') {
      steps {
        bat 'npm test a'
      }
    }
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