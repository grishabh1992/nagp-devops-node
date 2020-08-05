pipeline {
  agent any
 
  tools {nodejs "node-latest"}
 
  stages {
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
    stage('Test') {
      steps {
         sh 'npm test'
      }
    } 
  }
}