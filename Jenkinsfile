pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Welcome'
      }
    }

    stage('Test') {
      steps {
        echo 'Run unit tests'
      }
    }

    stage('Buzz Regression Tests') {
      steps {
        echo 'Buzz Regression Tests'
        echo 'Publish XML tests to JUnit'
      }
    }

    stage('Buzz Deploy') {
      steps {
        echo 'Deploy to staging server'
      }
    }

    stage('End') {
      steps {
        echo 'end'
      }
    }

  }
}