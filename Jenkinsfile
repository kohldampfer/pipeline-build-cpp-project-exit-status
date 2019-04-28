pipeline {

	agent any;

	stages {
		stage('Echo something') {
			steps {
				sh 'echo "Echo something"'
			}
		}

		stage('Build project') {
			steps {
				checkout scm
				sh 'make'
			}
		}
	}

}
