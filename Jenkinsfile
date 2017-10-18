pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello'
      }
    }
    stage('compile') {
      steps {
        sh 'mvn compile'
      }
    }
  }
}