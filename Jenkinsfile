pipeline {
	
    agent {label 'tomcat'}
    stages {
        stage('checkout'){
            
            steps{
		    echo scm :"${param.scm}"
            }
         }
        stage ('Compile Stage') {

            steps {
               echo "Hello world"
                
            }
        }

        stage ('Testing Stage') {
            
                steps {
                 echo "Hello world"
                }
            }
        


        stage ('Deployment Stage') {
            steps {
		    node ('dedgg') {
                 echo "Hello world"
		    }
            }
		    
        }
    }
}
