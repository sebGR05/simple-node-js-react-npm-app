pipeline {
	agent { 
		docker {
			image 'node-o-alpine'
			args '-p 3000:3000'
		}
	}
	stages {
		stage('Build') {
			steps {
				sh 'npn install'
			}
		}
	}
}
