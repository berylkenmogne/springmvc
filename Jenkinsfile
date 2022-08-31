pipeline {
agent any
  stages{
    stage('Build'){
      steps{
        sh "'${mvnHome}/bin/mvn' clean install"
      }
    }
    stage('Test'){
      steps{
      sh "'${mvnHome}/bin/mvn test'"
      }
    } 
  }
} 
