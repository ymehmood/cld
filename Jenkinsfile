pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
echo $M2_HOME
echo $MAVEN_HOME
mvn -B -DskipTests clean package'''
      }
    }
  }
}