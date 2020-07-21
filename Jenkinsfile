pipeline {
  agent {
    kubernetes true
  }

  stages {
    stage('Main') {
      steps {
        echo 'Hello world!'
      }
    }

    stage('Test') {
      steps {
        sh 'sleep 5'
        sh 'exit 0'
      }
    }
  }
}
