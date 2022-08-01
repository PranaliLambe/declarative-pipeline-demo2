pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo "this is build number ${BUILD_NUMBER} and ${DEMO}"
         bat '''
         
          echo "running a shell script"
          chmod +x test.sh
          ./test.sh
          
          '''
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
