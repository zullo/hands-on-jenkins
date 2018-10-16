pipeline {
  agent {
    node {
      label 'linux01'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
      }
    }
    stage('Test Chrome') {
      steps {
        sh 'echo \'Test Chrome\''
      }
    }
  }
}