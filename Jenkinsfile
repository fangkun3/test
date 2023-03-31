pipeline {
  agent any
  stages {
    stage('11') {
      steps {
        build 'pytest'
      }
    }

    stage('') {
      steps {
        sh 'echo \'${env}\''
      }
    }

  }
  environment {
    env = 'uat'
  }
}