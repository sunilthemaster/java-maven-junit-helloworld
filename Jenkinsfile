pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello'
      }
    }
    stage('Pulls') {
      steps {
        git(url: 'https://github.com/sunilthemaster/dataplatform.git', branch: 'master', credentialsId: '7b9188f3-00e8-4967-9dcd-520c678d79cc')
      }
    }
    stage('compile') {
      steps {
        sh 'mvn compile'
      }
    }
  }
}