// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
        string(defaultValue: "Hindu", description: 'What religion?', name: 'userFlag')
        choice(choices: ['Hindu', 'Muslim', 'Buddhist', 'Christian', 'Sikh'], description: 'What religion do you belong to?', name: 'religion')
        }
    stages{

        stage('First'){
                steps{
                    sh "mkdir ${params.userFlag}"
                    }
        }
        stage('Second'){
                steps{
                    writeFile(file: "filename.txt", text: "${params.userFlag}")
                    }
        }
        stage('Third'){
            steps{
                sh "pwd"
                }
        }
        stage('Chamatkar'){
            steps{
                echo "The parameter we decided upon is as: ${params.userFlag}"
                }
        }
    }
}
