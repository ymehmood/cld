pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
export M2_HOME=/opt/fedex/jks/apache-maven-3.2.5

mvn -v'''
      }
    }
  }
}