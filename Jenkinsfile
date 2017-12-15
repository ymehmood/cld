pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh 'sh \'mvn -B -DskipTests clean package\''
      }
    }
  }
}