pipeline {
  agent {
    label 'jdk9'
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