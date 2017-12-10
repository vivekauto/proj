pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        powershell 'get-service'
        junit(testResults: '*.xml')
      }
    }
  }
}
