pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            echo 'Test Start'
            node(label: 'Node')
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