pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
       echo "Build"
       sleep 10
      }
    }
     stage('Test'){
      steps {
       echo "Test Step"
       sleep 5
      }
    }
     stage('Deploy'){
      steps {
       echo "Deploy stage"
       sleep 7
      }
    }
     stage('Docker'){
      steps {
       echo "docker image"
       sleep 10
      }
    }
  }
} 