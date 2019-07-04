pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'python hello.py'
      }
    }
    stage('test') {
      steps {
        echo 'testing '
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy the code'
      }
    }
  }
}