pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        bat 'echo "this is ${BUILD_NUMBER} and and ${DEMO}"'
        echo '"this is bulid ${BUILD_NUMBER} and {DEMO}'
        echo '"this is build number ${BUILD_NUMBER} and ${DEMO1}"'
        echo '"this is build number ${BUILD_NUMBER} and ${DEMO}"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}