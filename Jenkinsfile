pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd cld/sms
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}