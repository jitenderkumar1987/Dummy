pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Welcome'
          }
        }

        stage('Step 1') {
          steps {
            echo 'Lets learn Jenkins'
          }
        }

      }
    }

    stage('End') {
      steps {
        echo 'Thanks'
      }
    }

  }
}