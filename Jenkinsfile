pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''cd sms
ls /Users/yasirmehmood/apache-maven-3.5.0
printenv
echo $M2_HOME
echo $MAVEN_HOME
mvn -B -DskipTests clean package'''
      }
    }
  }
}