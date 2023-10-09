pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/Trunkzs/creating-a-pipeline-in-blue-ocean', branch: 'master')
      }
    }

    stage('Install') {
      steps {
        sh 'apt-get update'
      }
    }

  }
}