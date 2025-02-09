pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Building the application..."'
        sh 'docker build -t react-router-app .'
      }
    }
  }
}