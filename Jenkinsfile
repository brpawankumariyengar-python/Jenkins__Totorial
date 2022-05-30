// Declarative //
pipeline{
    agent {label 'Computer'}
    environment{
            def Pawan__String = "Lankapati Dhashanan Gyani Veershiromani Raavan"
            def Pawan__Number = 108
            def Pawan__Boolean = true
        }
    stages{

        stage('Show__Variable__Values'){
                steps{
                    echo "Pawan String Value is  : ${Pawan__String}"
                    echo "Pawan String Value is  : ${Pawan__String}"
                    echo "Pawan String Value is  : ${Pawan__String}"
                    }
        }
        stage('Display__Deployment__Region'){
                steps{
                    echo "The deployment region  you selected is as   : ${params.deployRegion}"
                    }
        }
        stage('Completeion__Celebration'){
            steps{
                echo "Yaaaay ...Done Done Done"
                }
        }
    }
}