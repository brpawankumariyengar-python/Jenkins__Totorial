// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
            string(defaultValue: "Lankapati__Ravan", description: 'Please enter your Deployment Name', name: 'deploymentName')
        }
    stages{

        stage('Show__Variable__Values'){
                steps{
                    echo " The  Value is as:   ${deploymentName}"
                        //Pawan__Function("${deploymentName}")
                    }
        }
        stage('Completeion__Celebration'){
            steps{
                echo "Yaaaay ...Done Done Done... Ho gaya"
                }
        }
    }
}

def Pawan__Function(String Tota){
 def Ctr = 0
 while(Ctr < 20){
    echo "Ho Gaya na ${Ctr} and the string value is  :${Tota}"
    Ctr = Ctr + 1
 }
}
