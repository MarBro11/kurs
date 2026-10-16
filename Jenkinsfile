pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				checkout scm
				sh 'echo 123 > test.html'
			}
		}
		stege('Test') {
			steps {
				checkout scm
				sh 'test -f test.html'
			}
		
		}
	}
}
