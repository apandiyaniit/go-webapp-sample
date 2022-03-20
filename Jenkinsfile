pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh 'sh \'go ./...\''
          }
        }

        stage('test1') {
          steps {
            sh 'sh \'whoami\''
          }
        }

      }
    }

  }
}