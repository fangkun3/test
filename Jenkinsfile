pipeline {
  agent any
  stages {
    stage('11') {
      steps {
        build 'pytest'
      }
    }

  }
  environment {
    env = 'uat'
  }
}