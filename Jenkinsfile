// Declarative //
pipeline{
    agent {label 'Computer'}
    parameters{
        string(defaultValue: "Gogo gaga nana mama", description: 'Please Enter Text here', name: 'userFlag')
        }
    stages{

        stage('First'){
                steps{
                    sh "mkdir ${param.userFlag}"
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
