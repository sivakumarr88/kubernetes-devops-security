pipeline {
	agent any
	
	stages {
		stage('Build') {
			steps {
				sh "mvn clean package -DskipTests=true"
			}
		}
		stage('Unit Test') {
			steps {
				sh "mvn test"
			}
		}
		stage('Krishna') {
			steps {
				sh "echo krishna pipeline"
			}
		}
	}
}