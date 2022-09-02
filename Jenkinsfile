pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'pwsh --version'
      }
    }
    stage('hello') {
      steps {
        sudo pwsh -command "hello.ps1"
      }
    }
  }
}
