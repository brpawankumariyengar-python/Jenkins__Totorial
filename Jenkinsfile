// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
        string(defaultValue: "Why? Why? Why?", description: '', name: 'userFlag')
        }
    stages{

        stage('First'){
                steps{
                    echo 'First First First'
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
