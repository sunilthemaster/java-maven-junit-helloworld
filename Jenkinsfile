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
        git(url: 'https://github.com/sunilthemaster/dataplatform.git', branch: 'master', credentialsId: 'sunilthemaster')
      }
    }
  }
}