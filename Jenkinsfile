pipeline {
	agent any
	stages {
		stage('Build') {
			whne {
				changelog '.*some_text.*'
			}
			steps {
				echo 'Test line 12'
			}
		}
	}
}
			
