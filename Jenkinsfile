pipeline {

	agent any;

	stages {
		stage('Echo something') {
			steps {
				sh 'echo "Echo something"'
			}
		}

		stage('Exit with error') {
			steps {
				sh 'make'
			}
		}
	}

}
