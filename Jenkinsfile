pipeline {
agent none
stages { 
	stage ('all shit') {
  parallel {
        stage('Build') {
		
		 agent { label 'master' }
            steps {
                
		    script{
			    echo 'Building..'
		             sleep 20
		    	  }
				 }
		}
				
				
		stage('deploy') {
			
		 agent { label 'master' }
            steps {
                script{
			    echo 'Building..'
		             sleep 20
		    	  }
				 }
				}
		stage('test') {
			
		 agent { label 'master' }
            steps {
                 script{
			    echo 'Building..'
		             sleep 20
		    	  }
				 }
				}		
		}	
		}
		}
		}
	
