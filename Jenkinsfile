pipeline {
  agent{docker{image 'microsoft/iis'
               args '-d -p 80:80'
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
