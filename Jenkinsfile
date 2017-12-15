pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
man help
sh \'mvn -X -DskipTests clean package\''''
      }
    }
  }
}