pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
man help
sh \'${M2_HOME}/bin/mvn -X -DskipTests clean package\''''
      }
    }
  }
}