pipeline {
  agent any
  stages {
    stage('initialize') {
      agent any
      steps {
        bat(script: 'hello', encoding: 'UTF-8')
      }
    }
  }
}