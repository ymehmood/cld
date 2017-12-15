pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''pwd
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}