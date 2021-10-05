pipeline {
  agent {
    label 'jdk17'
  }
  stages {
    stage('SayHello') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }

  }
}