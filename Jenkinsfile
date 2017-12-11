pipeline {
  agent any
  stages {
    stage('Initialize') {
            steps {  bat 'java --version'
                   bat 'docker pull hello-world'
          }
    }
  }
}
