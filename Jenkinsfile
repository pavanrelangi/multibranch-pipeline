pipeline { 
  
   agent any

   stages {
     stage('git checkout') {
   steps {
     git branch: 'dev', url: 'https://github.com/pavanrelangi/multibranch-pipeline.git'
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
