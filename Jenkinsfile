// Declarative //
pipeline {
	agent any 
	stages {
		stage('Build') {
			when{
				branch 'master'
			}
			steps { 
				echo "Building on master"
			}
		}
		stage('Build') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Building on dev"
			}
		}
		stage('Test') {
			when{
				branch 'master'
			}
			steps { 
				echo "Testing on master"
			}
		}
		stage('Test') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Testting on dev"
			}
		}
		stage('Deploy') {
			when{
				branch 'master'
			}
			steps { 
				echo "Deploying on master"
			}
		}
		stage('Deploy') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Deploying on dev"
			}
		}
	}
}
