pipeline {
  agent any
  stages {
    stage('buzz build') {
      agent any
      steps {
        sh '''#!/bin/bash
./jenkins/script.sh'''
      }
    }

    stage('buzz test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}