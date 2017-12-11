pipeline {
  agent none
  stages {
    stage('Initialize') {
      agent{docker{image 'maven:3-alpine'}}
      steps {  bat 'mvn --version'
          }
    }
  }
}
