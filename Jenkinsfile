pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           rsh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           rsh 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           rsh 'echo "deploying application..."'
         }

     }
  
   	}

   }
