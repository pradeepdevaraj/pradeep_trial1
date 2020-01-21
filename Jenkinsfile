pipeline {
agent none
stages { 
	stage ('all shit') {
  
        stage('Build') {
		
		 agent { label 'master' }
		 steps ('all parallel shit') {
		 parallel {
		 
            steps ('build 1.1') {
                
		    script{
			    echo 'Building..'
		             sleep 20
		    	  }
				 }
				 
			steps ('build 1.2') {
                
		    script{
			    echo 'Building 22..'
		             sleep 20
		    	  }
				}
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
		
	
