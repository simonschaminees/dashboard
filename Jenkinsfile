pipeline {

  agent any
  
  stages {
  
    stage("build") {
    
      steps {
      echo 'start building'
        nodejs('node-16.14.0'){
         sh 'npm install' 
        }
      }
    }
 
    stage("test") {
    
      steps {
      echo 'testing'
      }
    }
    
    stage("deply") {
    
      steps {
      echo 'deploy'
      }
    }    
    
  }
}
