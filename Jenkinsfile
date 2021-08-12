pipeline {
  agent any
  stages {
    stage('buzz build') {
      steps {
        sh './jenkins/buixxxxxld.sh'
      }
    }

    stage('buzz test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}