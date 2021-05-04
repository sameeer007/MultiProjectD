pipeline {
    agent {label 'tomcat'}
	stages {
		
	stage{
		step('checkout'){
			checkout SCM
		} 
	}	
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3_8_1') {
                    sh 'mvn clean compile'
                }
            }
        }

        stage ('Testing Stage') {
            
                steps {
                withMaven(maven : 'maven_3_8_1') {
                    sh 'mvn test'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
			    node ('jenkins-slave') 
                withMaven(maven : 'maven_3_8_1') {
                    sh 'mvn deploy'
                }
            }
        }
    }
}
