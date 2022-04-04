pipeline {

  agent any
  
  stages {
  
    stage("build") {
    
      steps {
      echo 'start building'
      sh 'npm install'
      }
    }
    
    stage("testing") {
    
      steps {
      echo 'start testing'  
      }
    } 
    
    stage("deply") {
    
      steps {
      echo 'start deploy'  
      }
    } 
    
    
  }
}
