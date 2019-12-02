pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Jenkins Pipiline'
          }
        }
        stage('Inititalise') {
          steps {
            sh '''echo "hi
"; echo "hello"'''
          }
        }
      }
    }
  }
}