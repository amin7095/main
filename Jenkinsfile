pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'powershell --version'
      }
    }
    stage('hello') {
      steps {
        sh 'pwsh hello.ps1'
      }
    }
  }
}
