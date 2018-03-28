pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build'
            echo 'New Build'
          }
        }
        stage('Build3') {
          steps {
            echo 'Test'
          }
        }
        stage('Build4') {
          steps {
            echo 'Test2'
          }
        }
        stage('Build5') {
          steps {
            echo 'Test3'
          }
        }
      }
    }
    stage('Unit Test') {
      steps {
        echo 'Test'
      }
    }
    stage('Automated Test') {
      steps {
        echo 'Automated Test'
      }
    }
    stage('Deploy to Dev') {
      steps {
        echo 'Deployed'
      }
    }
  }
}