pipeline {
  agent any
  stages {
    stage('buzz build') {
      steps {
        sh './jenkins/buixxxxld.sh'
      }
    }

    stage('buzz test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}
