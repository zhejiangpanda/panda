pipeline {
  agent any
  stages {
    stage('first') {
      parallel {
        stage('first') {
          steps {
            echo 'test2'
            echo 'test3'
          }
        }
        stage('second') {
          steps {
            echo 'test4'
          }
        }
      }
    }
    stage('third') {
      steps {
        sleep 2
      }
    }
  }
}