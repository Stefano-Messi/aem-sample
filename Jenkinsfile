pipeline {
  agent {
    docker {
      image 'maven:3.6-alpine'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}