pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm i'
      }
    }

    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}
