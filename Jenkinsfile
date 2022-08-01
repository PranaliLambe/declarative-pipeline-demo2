pipeline {
  agent any
  environment {
      RELEASE='20.04'
      }
  stages {
    stage('Build') {
      environment {
        LOG_LEVEL='INFO'
        }
      steps {
        echo "this is build number ${RELEASE} and ${LOG_LEVEL}"
        
      }
    }
    stage('Test'){
      steps{
          echo "Testing Release ${RELEASE}"
          writeFile file: 'test-result.txt',test: 'passed'
          }
          }
}
post {
  success {
    archiveArtifact 'test-results.txt'
    }
  }
}
