pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
man help
sh \'${mvnHome}/bin/mvn -B -DskipTests clean package\''''
      }
    }
  }
}