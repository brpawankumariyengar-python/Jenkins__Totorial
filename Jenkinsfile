// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
        string(defaultValue: "Lankapati__Ravan", description: 'Please enter your Deployment Name', name: 'deploymentName')
        choice(choices:["EU-WEST-2A","EU-WEST-2B","EU-WEST-2C"], description: "Enter the region you want to deploy to", name: 'deployRegion')
        boolean(defaultValue: false, description: "Do you want to deploy???", name: 'deployDecision')
        }
    stages{

        stage('Display__Deployment__Name'){
                steps{
                    echo "The deployment name you typed in is as   : ${params.deploymentName}"
                    }
        }
        stage('Display__Deployment__Region'){
                steps{
                    echo "The deployment region  you selected is as   : ${params.deployRegion}"
                    }
        }
        stage('Chamatkar'){
            steps{
                echo "The deployment decision you made is as   : ${params.deployDecision}"
                }
        }
    }
}