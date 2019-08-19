pipeline {
	      agent any	 

 	      stages {	
 		            stage('Integration test') {
			                  steps {
				                    sh 'aws cloudformation deploy --template-file ECR.yml --stack-name my-ecr-repo'					
			                  }
		            }				
	      }		 	
}
