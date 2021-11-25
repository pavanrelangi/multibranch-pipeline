pipeline { 
  
   agent any

   stages {
   
     stage('Install python') { 
        steps { 
           sh 'yum install python' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
