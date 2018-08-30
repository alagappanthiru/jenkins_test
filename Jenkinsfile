pipeline {
  agent any
  stages {
    stage('say hello') {
      steps {
        echo 'hello AL'
      }
    }
    stage('shell script') {
      steps {
        sh 'java -version'
      }
    }
  }
}