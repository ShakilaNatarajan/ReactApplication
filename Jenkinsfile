pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        bat 'npm install '
      }
    }
    stage('Coverage') {
      steps {
        bat 'npm test a'
      }
    }
  }
  tools {
    nodejs 'node'
  }
  triggers {
    cron('H * * * *')
  }
}