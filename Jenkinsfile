pipeline {
  agent any
  stages {
    stage('stages') {
      steps {
        sh '''sh \'cd cld\'
sh \'mvn -B -DskipTests clean package\''''
      }
    }
  }
}