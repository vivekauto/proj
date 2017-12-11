pipeline {
  agent none
  stages {
    stage('Initialize') {
      agent{docker{image 'microsoft/WindowsServercore'}}
      steps {  bat 'java --version'
          }
    }
  }
}
