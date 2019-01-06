pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'echo "demo dev"'
      }
    }
    stage('test') {
      steps {
        sh 'echo "test"'
      }
    }
    stage('prod') {
      steps {
        echo 'prod'
      }
    }
  }
}