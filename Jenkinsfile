pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
      
        echo "this is build number ${BUILD_NUMBER} and ${DEMO}"
      }
    }

  }
  environment {
    DEMO = "1"
  }
}
