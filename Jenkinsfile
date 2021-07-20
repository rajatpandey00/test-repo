pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            echo 'Test Start'
          }
        }

        stage('Install') {
          steps {
            echo 'Installing dependencies'
          }
        }

      }
    }

  }
}