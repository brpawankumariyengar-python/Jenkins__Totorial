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
                    Pawan__Function(" ${deploymentName} ")
                    }
        }
        stage('Completeion__Celebration'){
            steps{
                echo "Yaaaay ...Done Done Done ... Congratulations  ... Ho gaya"
                }
        }
    }
}

def Pawan__Function(String Input__Value){
 def Ctr = 1
 while(Ctr < 21){
    echo "Ho Gaya na ${Ctr} and the string value is  :${Input__Value}"
    Ctr = Ctr + 1
 }
}
