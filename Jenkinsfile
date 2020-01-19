pipeline {
agent any
stages {
        stage('Build_check') {
            steps {
                echo 'Building..'
				sh 'pwd; chmod 777 build deploy test; ./build'
				
            }
        }
      }
}
                    
