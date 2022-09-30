pipeline {
  agent any
  stages {
    stage('build'){
      steps {
        echo " Building the application .."
      }
    
    
    }
    stage('Test'){
      steps {
        ech " Testing the application .."
      }
    
    
    }
    stage('Run'){
      steps {
        echo " Running the application .."
      }
    
    
    }
  
  
  
  }
  post {
    success {
      echo " Succesfully steup the pipeline .. "
    }
    failure {
      echo " failed setting up the pipeline .."
    }
  
  }
  


}
