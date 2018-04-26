pipeline {
  agent any
  stages {
    stage('Verify') {
      steps {
        bat 'mvn compile'
      }
    }
    stage('Test') {
      steps {
        bat 'mvn clean'
        bat 'mvn test'
      }
    }
  }
}