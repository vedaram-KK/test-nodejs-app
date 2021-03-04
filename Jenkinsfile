pipeline { 
  
   agent any

   stages {
   
     stage('Install Required Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy the node application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
