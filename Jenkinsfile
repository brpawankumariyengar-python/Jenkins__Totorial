// Declarative //
pipeline{
	agent {label 'Computer'}
	parameters{
		booleanParam(defaultValue: false, description: 'True or False', name: 'pawanBoolean')
		}
	stages{

		stage('First'){
				steps{
					echo 'First First First'
					}
		}
		stage('Second'){
				steps{
					echo 'Second Second Second'
					}
		}
		stage('Third'){
			steps{
				sh "pwd"
				}
		}
		stage('Chamatkar'){
			steps{
				echo "The parameter we decided upon is as: ${params.pawanBoolean}"
				}
		}
	}

}
