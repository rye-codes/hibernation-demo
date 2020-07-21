pipeline {
  agent {
    kubernetes true
  }

  stages {
    stage('Clone') {
      steps {
        checkout scm
      }
    }

    stage('Main') {
      steps {
        echo 'Hello world!'
      }
    }

    stage('Test') {
      steps {
        sh 'sleep 30'
        sh 'exit 1'
      }
    }
  }
}
