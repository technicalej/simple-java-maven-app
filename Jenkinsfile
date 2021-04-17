pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mydocker"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
