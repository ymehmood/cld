pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
mvn -B -DskipTests clean package'''
      }
    }
  }
}