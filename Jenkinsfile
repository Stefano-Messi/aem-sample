pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('error') {
      steps {
        echo 'hello'
        sh 'mvn clean install'
      }
    }

  }
}