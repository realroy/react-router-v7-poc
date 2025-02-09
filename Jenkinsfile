pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ls -la'
        sh 'echo "Building the application..."'
        sh 'docker build -t react-router-app .'
      }
    }
  }
}