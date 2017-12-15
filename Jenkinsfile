pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
pwd
ls
cd /
ls
mvn -B -DskipTests clean package'''
      }
    }
  }
}