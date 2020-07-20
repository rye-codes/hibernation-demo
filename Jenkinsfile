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
  }
}

