pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mymaven3"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
