pipeline {
  agent {
      label 'master'
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
