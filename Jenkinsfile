pipeline {

  agent any
  
  stages {
  
    stage("build") {
    
      steps {
      echo 'start building'
          nodejs('node-16.14.0'){
         batch 'npm install' 
        }
      }
    }
    
    
  }
}
