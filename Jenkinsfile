pipeline {
agent none
stages {
        stage('Build') {
		parallel {
		 agent { label 'master' }
            steps {
                
		    script{
			    echo 'Building..'
		             sleep 20
		    	  }
				 }
		}
				}
				
		stage('deploy') {
			parallel {
		 agent { label 'master' }
            steps {
                script{
			    echo 'Building..'
		             sleep 20
		    	  }
	    }
				 }
				}
				
		stage('test') {
			parallel {
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
             


