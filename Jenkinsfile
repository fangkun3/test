pipeline {
  agent any
  stages {
    stage('11') {
      steps {
        build 'pytest'
      }
    }

    stage('echo') {
      steps {
        sh 'echo ${env}'
      }
    }

  }
  environment {
    env = 'uat'
  }
}