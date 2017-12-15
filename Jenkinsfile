pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
man clean package
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}