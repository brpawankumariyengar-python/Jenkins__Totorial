// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
        choice(choices: ['Hindu', 'Muslim', 'Buddhist', 'Christian', 'Sikh'], description: 'What religion do you belong to?', name: 'religion')
        }
    stages{

        stage('First'){
                steps{
                    sh "mkdir ${params.religion}"
                    }
        }
        stage('Second'){
                steps{
                    writeFile(file: "filename.txt", text: "${params.religion}")
                    }
        }
        stage('Third'){
            steps{
                sh "pwd"
                }
        }
        stage('Chamatkar'){
            steps{
                echo "The parameter we decided upon is as: ${params.religion}"
                }
        }
    }
}
