pipeline {
  agent any
  stages {
    stage('initialize') {
      agent any
      steps {
        echo 'minimal pipeline'
        bat(script: 'hello.bat', returnStatus: true)
      }
    }
  }
}