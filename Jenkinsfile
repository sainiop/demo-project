pipeline {
  agent any
  
  stages {
    stage("build"){
      steps{ 
        echo "it is build stage..." 
      }
    }
    stage("test"){
      when {
        expression {
          params.executeTests
        }
      }
    }
    stage("deploy"){
      steps{ 
        echo "it is deploy stage..." 
      }
    }
  }
}
    
    
    
