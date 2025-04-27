pipeline {
	agent any
	stages {
		stage('Hello') {
			steps {
				echo "Hello from MAIN branch"
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
