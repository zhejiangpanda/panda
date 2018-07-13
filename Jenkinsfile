pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        echo 'test2'
        echo 'test3'
        timeout(activity: true, time: 2) {
          echo 'enforce time 2 second'
        }

      }
    }
    stage('third') {
      steps {
        sleep 2
      }
    }
    stage('fouth') {
      steps {
        echo 'test4'
      }
    }
    stage('firth') {
      steps {
        echo 'test5'
      }
    }
  }
}