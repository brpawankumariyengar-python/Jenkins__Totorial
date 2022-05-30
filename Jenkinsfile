// Declarative //
pipeline{
    agent {label 'Computer'}
    stages{

        stage('Show__Environment__Variable__Values'){
                steps{
echo "The Build Number is  : ${env.Build_Number}"
echo "The Job Name is  : ${env.Job_Name}"
echo "The Node Name is  : ${env.NODE_NAME}"
echo "The Node Name is  : ${env.NODE_NAME}"
echo "The  Workspace Path is  : ${env.WORKSPACE}"
echo "The executor Number is   :${env.EXECUTOR_NUMBER}"
echo "The Build Tag is   :${env.BUILD_TAG}"
echo "The Java Home is:   :${env.JAVA_HOME}"
                    }
        }
        stage('Completeion__Celebration'){
            steps{
                echo "Yaaaay ...  Congratulations    ...   Done Done Done"
                }
        }
    }
}
