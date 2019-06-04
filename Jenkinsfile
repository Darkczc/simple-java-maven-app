pipeline {
  agent {
    node {
      label 'node1'
    }

  }
  stages {
    stage('Build1') {
      steps {
        sh 'npm install'
      }
    }
  }
}