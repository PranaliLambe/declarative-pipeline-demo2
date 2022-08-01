pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        bat 'echo "this is ${BUILD_NUMBER} and and ${DEMO}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}