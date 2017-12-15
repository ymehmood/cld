pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
${M2_HOME}/bin/mvn -B -DskipTests clean package'''
      }
    }
  }
}