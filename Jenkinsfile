pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo 'This is build number $BUILD_NUMBER of demo $DEMO'
      }
    }

  }
  environment {
    DEMO = '1-2'
  }
}