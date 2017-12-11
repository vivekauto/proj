pipeline {
  agent{docker{image 'microsoft/iis'
               args '-p 80:80'
              }
       }
  stages {
    stage('Initialize') {
      steps {
        powershell 'get-service'
          }
    }
  }
}
