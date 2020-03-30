pipeline{
	agent any
	
	stages{
		stage('Build Stage'){
			when{
			  changelog 'Build'
			}
			steps{
				echo "This Stage is used for Build"
			}
		}
		stage('Deploy Stage'){
			when{
				changelog 'Deploy'
			}
			steps{
				echo "This stage is used for Deploy"
			}
		}
	}
}