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
}