pipeline {
	
    agent {label 'tomcat'}
	stages {
        stage ('Compile Stage') {

            steps {
               echo "Hello world"
                
            }
        }
	 stage ('build Stage') {
            
                steps {
                 echo "Hello worlsamd"
                }
            }	

        stage ('Testing Stage') {
            
                steps {
                 echo "Hello worlsaddmd"
                }
            }
		
		
        stage ('UAT Stage') {
            
                steps {
                 echo "Hello worlsamd"
                }
            }


        stage ('Deployment Stage') {
            steps {
		    node ('dedgg') {
                 echo "Hello worldsameesddr"
		    }
            }
		    
        }
    }
}
