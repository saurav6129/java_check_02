pipeline {
	agent any 
	stages {
		stage('Java check') {
			agent {
				docker {
					image 'node:6-alpine'
				
				}
		
			}
		
			steps {
				
				sh'./jenkins/script/test.sh'
			}
		}
		
	}

}
