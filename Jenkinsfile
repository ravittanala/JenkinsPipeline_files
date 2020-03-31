/*pipeline{
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
}*/

pipeline{
	agent any
	
	stages{
		stage('Java'){
			when{
			  changeset '*.java'
			}
			steps{
				echo "This is Java Program"
			}
		}
		stage('Perl'){
			when{
				changeset '*.pl'
			}
			steps{
				echo "This is Perl program"
			}
		}
	}
}