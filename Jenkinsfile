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
        bat 'npm test a --forceExit'
      }
    }
  }
  tools {
    nodejs 'node'
  }
  triggers {
    pollSCM('* * * * *')
  }
}