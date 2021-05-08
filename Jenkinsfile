pipeline {
	
    agent {label 'tomcat'}
	stages {
        stage ('Compile Stage') {

            steps {
               echo "Hello worrld"
                
            }
        }
	 stage ('build Stage') {
            
                steps {
                 echo "Hello xghcworfslsamd"
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
		
		Stage ('code commit stage') {
			steps{
			echo('test commit changes in jenkins ci/cd pipeline')
			}
		}
			
    }
}
