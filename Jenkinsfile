pipeline { 
  
   agent any

   stages {
   
     stage('Install clean') { 
        steps { 
           sh 'mvn clean install' 
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
