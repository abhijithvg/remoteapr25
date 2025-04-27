pipeline {
	agent any
	stages {
		stage('Hello') {
			steps {
				echo "Hello from DEMO branch"
			}
		}
		stage('print stage') {
			when {
				branch 'demo'
			}
			steps {
				sh 'cat demo1.txt'
			}
		}
	}
}
