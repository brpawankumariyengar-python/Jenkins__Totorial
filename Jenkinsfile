// Declarative //
pipeline{
	agent {label 'Computer'}
	parameters{
		booleanParam(defaultValue: false, description: 'True or False', name: 'Please_check_the_box_for_True_or_leave_blank_for_False')
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
				echo "The parameter we decided upon is as: ${params.Please_check_the_box_for_True_or_leave_blank_for_False}"
				}
		}
	}

}
