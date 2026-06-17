pipeline {
  agent any
  stages {
    stage('Build') {
      step {
        bat 'mvn clean compile'
      }
    }

    stage('Test') {
      step {
        bat 'mvn test'
      }
    }

    stage('Package') {
      step {
        bat 'mvn package'
      }
    }

    stage('Deploy') {
      step {
        echo 'ApplicationSuccesfully Deployed"
      }
    }
    
