pipeline {
  agent {
    node {
      label 'node:lts-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'yum install'
      }
    }

  }
  environment {
    docker = ''
  }
}