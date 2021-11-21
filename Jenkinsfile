pipeline {
  agent {
    node {
      label 'docker-env'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Testes') {
      steps {
        echo 'testing'
      }
    }

    stage('Deploy') {
      steps {
        sh 'docker ps -a'
      }
    }

  }
}