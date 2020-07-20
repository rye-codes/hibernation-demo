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
  }
}

