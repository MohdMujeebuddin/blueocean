pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh '''ls
pwd'''
          }
        }

        stage('') {
          steps {
            echo 'hello'
          }
        }

      }
    }

    stage('build') {
      steps {
        sleep 10
      }
    }

    stage('prod') {
      steps {
        sleep 5
      }
    }

  }
}