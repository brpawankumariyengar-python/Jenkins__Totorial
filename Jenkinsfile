pipeline {
    agent any
    stages {
        stage("Barfi"){
            steps {
                writeFile(file: "filename.txt", text: "Hule Hulare Hule Hule Hule")
            }
        }
        stage("Jalebi"){
            steps {
                sh "git clone https://github.com/jenkins-docs/simple-java-maven-app.git"
            }
        }
        stage("Pakoda"){
            steps {
                    echo "Hona tha  .... Ho Gaya"
                   }
            }
    }
}
