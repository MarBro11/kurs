pipeline {
	agent any

	stage('Build') {
		steps {
			sh 'echo 123 >test.html'
		}
	}
	stege('Test') {
		steps {
			checkout scm
			sh 'test -f test.html'
		}
	}
}
