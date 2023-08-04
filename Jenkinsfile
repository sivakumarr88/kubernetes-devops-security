pipeline {
	agent any
	
	stages{
		stage('Build and Archive') {
			steps {
				sh "mvn clean package -DskipTests=true"
				archive "target/*.jar"
			}
		}
	}
}