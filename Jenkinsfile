pipeline {

  agent any
  
  stages {
  
    stage("build") {
    
      steps {
      echo 'start building'  
      sh 'npm install'
      sh 'npm build'  
      }
    }   
  }
}
