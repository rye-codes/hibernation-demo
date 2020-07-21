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
        sh 'exit 0'
      }
    }
  }
}
