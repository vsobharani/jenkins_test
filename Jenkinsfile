pipeline {
	
	parameters {
		booleanParam(name: 'DEPLOY', defaultValue: false, description: 'Do you want to Deploy?')
	}	
	
	agent any 
	stages {
		stage('BUILD') {
			steps {
				script {
					if (params.DEPLOY) {
						echo "true: $DEPLOY"
					}
				}
			}
		}
	}
}
