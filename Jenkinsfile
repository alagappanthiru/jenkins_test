pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'hello AL'
        sh 'java -version'
      }
    }
  }
}