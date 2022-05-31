// Declarative //
pipeline{
	agent {label 'Computer'}
	parameters{
		booleanParam(defaultValue: false, description: 'True or False', name: 'Please_check_the_box_for_True_or_leave_blank_for_False')
		}
	stages{

		stage('Check__Decision'){
			steps{
				script{
					if(params.Please_check_the_box_for_True_or_leave_blank_for_False == true){
						echo "All is good. All is True. Happy... Joy"
						}
					else{
						echo"All are lies. All is false. Sad ... Depressed"
						}
					}
			}
		}
		stage('Completed__Celebration'){
			steps{
				echo "Success...  Yaay ... Happy ... Congratulations"
				}
		}
	}

}
