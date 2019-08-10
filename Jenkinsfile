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
				                    sh 'aws cloudformation deploy --template-file /fargate-cloudformation-example
/ECR.yml --stack-name ECR-Stack'					
			                  }
		            }				
	      }		 	
}
