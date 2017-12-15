pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}