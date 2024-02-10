pipeline {
  agent any
  stages {
    stage('Checkout ') {
      steps {
        git(url: 'https://github.com/waladevops/kawla', branch: 'main')
      }
    }

    stage('shell') {
      steps {
        sh 'ls -al'
      }
    }

  }
}