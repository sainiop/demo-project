pipeline {
  agent any
  
  stages {
    stage("build"){
      steps{ 
        echo "it is build stage..." 
      }
    }
    stage("test"){
      steps {
        expression {
          params.executeTests
        }
        echo "test......."
      }
    }
    stage("deploy"){
      steps{ 
        echo "it is deploy stage..." 
      }
    }
  }
}
    
    
    
