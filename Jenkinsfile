pipeline {
agent none
stages {
        stage('Build') {
		 agent { label 'master' }
            steps {
                echo 'Building..'
				 sh sleep 120
				 }
				}
				
		stage('deploy') {
		 agent { label 'master' }
            steps {
                echo 'deploy..'
				 sh sleep 120
				 }
				}
				
		stage('test') {
		 agent { label 'master' }
            steps {
                echo 'test..'
				 sh sleep 120
				 }
				}		
				
				
		}
	}
                    
