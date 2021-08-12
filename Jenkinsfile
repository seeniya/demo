pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hi world'
      }
    }

    stage('stage2') {
      steps {
        echo 'hi seeniya'
        sh 'echo Another Placeholder'
      }
    }

    stage('stage3') {
      steps {
        sh 'hostname'
        sh 'sleep 5'
      }
    }

  }
}