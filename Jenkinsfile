pipeline {
   agent {
        docker {
            image 'docker:latest'
            args '-v /var/run/docker.sock:/var/run/docker.sock --network jenkins'
        }
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