pipeline {
	agent any 
	stages('Java check') {
		agent {
			docker {
				image 'node:6-alpine'
				
			}
		
		}
		
		steps {
			sh 'npm install'
			sh'./jenkins/script/test.sh'
		
		}
	}

}
