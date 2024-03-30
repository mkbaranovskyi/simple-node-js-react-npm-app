pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm i'
        sh 'npm run ci-test'
      }
    }

    stage('Test') {
      steps {
        sh './jenkins/scripts/test.sh'
      }
    }
  }
}
