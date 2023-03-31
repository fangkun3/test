pipeline {
  agent any
  stages {
    stage('11') {
      agent any
      environment {
        env = 'uat'
      }
      steps {
        build 'pytest'
      }
    }

    stage('echo') {
      steps {
        sh 'echo $env'
      }
    }

  }
  environment {
    env = 'uat'
  }
}