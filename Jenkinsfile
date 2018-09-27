pipeline {
  agent any
  stages {
    stage('OK') {
      parallel {
        stage('OK') {
          steps {
            echo 'OK'
          }
        }
        stage('') {
          steps {
            error 'le code n\'as pas fonctionne'
          }
        }
      }
    }
  }
}