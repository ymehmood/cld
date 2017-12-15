pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''pwd
ls
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}