pipeline {
  agent any
  stages {
    stage('Verify') {
      steps {
        bat 'mvn verify'
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