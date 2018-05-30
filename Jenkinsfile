// Declarative //
pipeline {
	agent any 
	stages {
		stage('Build_m') {
			when{
				branch 'master'
			}
			steps { 
				echo "Building on master"
			}
		}
		stage('Build_d') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Building on dev"
			}
		}
		stage('Test_m') {
			when{
				branch 'master'
			}
			steps { 
				echo "Testing on master"
			}
		}
		stage('Test_d') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Testting on dev"
			}
		}
		stage('Deploy_m') {
			when{
				branch 'master'
			}
			steps { 
				echo "Deploying on master"
			}
		}
		stage('Deploy_d') {
			when{
				branch 'dev'
			}
			steps { 
				echo "Deploying on dev"
			}
		}
	}
}
