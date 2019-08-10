pipeline {
	      agent any	 

 	      stages {
               stage('Build') {
                        steps {
                            sh 'env'
                        }
                }		
 		            stage('Integration test') {
			                  steps {
				                    sh 'aws cloudformation deploy --template-file ECR.yml --stack-name my-ecr-repo'					
			                  }
		            }				
	      }		 	
}
