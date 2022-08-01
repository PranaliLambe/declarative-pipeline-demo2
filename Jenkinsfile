pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo "this is build number ${BUILD_NUMBER} and ${DEMO}"
        sh '''
          #!C:/Program Files/Git/bin/bash.exe
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
