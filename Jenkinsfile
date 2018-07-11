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
        stage('') {
          steps {
            echo 'test4'
          }
        }
      }
    }
    stage('') {
      steps {
        sleep 2
      }
    }
  }
}