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
				                    sh 'ansible-playbook ECR.yml'					
			                  }
		            }				
	      }		 	
}
