pipeline {
  agent any
  stages {
    stage('Coverage') {
      steps {
        bat 'npm react-scripts test'
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