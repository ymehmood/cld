pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
export M2_HOME=/Users/yasirmehmood/apache-maven-3.5.0

$M2_HOME/bin/mvn -v'''
      }
    }
  }
}