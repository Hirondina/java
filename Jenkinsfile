pipeline {
  agent any
  stages {
    stage('initialize') {
      steps {
        git 'https://github.com/Hirondina/java.git'
      }
    }
    stage('Build') {
      steps {
        echo 'Sucesso'
      }
    }
    stage('Test') {
      steps {
        build 'teste'
      }
    }
  }
}
