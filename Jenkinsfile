pipeline {
  agent any
  stages {
    stage('Devolopment') {
      steps {
        echo '"success"'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            echo '"unit test"'
          }
        }

        stage('integration') {
          steps {
            echo 'done successfully'
          }
        }

      }
    }

  }
}