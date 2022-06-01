// Declarative //
pipeline{
    agent {label 'Computer'}
    stages{

        stage('Multple__Bash__Script__Lines'){
                steps{
                    sh """
                        pwd
                        whoami
                        ls -a
                        printenv
                        """
                    }
        }
        stage('Trigger__Another__Pipeline'){
            steps{
                build 'hello-world-jenkins'
            }
        }
        stage('Completeion__Celebration'){
            steps{
                echo "Yaaaay ...Done Done Done... Ho gaya"
                }
        }
    }
}
