pipeline{
	agent any
	stages {
		stage('compile') {
			steps {
				echo 'hi this is compile step'
			}
			
		}
		stage('build') {
			steps {
				sh 'javac Hello.java'
				sh 'java Hello'
			}
		}
	}
}
