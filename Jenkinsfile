pipeline {
		agent any
		stages {
			stage('Build') {
				steps {
					echo "Build"
				}
			}
			stage('Test') {
				steps {
					echo "Test"
				}
			}
			stage('BIntegration Testuild') {
				steps {
					echo "Integration Test"
				}
			}
		} 
		
		post {
			always {
				echo 'Im awesome. I run always'
			}
			success {
				echo 'I run when you are successful'
			}
			always {
				echo 'I run when you fail'
			}
		}
}
