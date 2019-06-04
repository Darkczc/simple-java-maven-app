pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}