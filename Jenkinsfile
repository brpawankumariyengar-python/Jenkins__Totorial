pipeline {
    agent any
    stages {
        stage("Barfi"){
            steps {
                deleteDir()
            }
        }
        stage("Jalebi"){
            steps {
                sh "git clone https://github.com/jenkins-docs/simple-java-maven-app.git"
            }
        }
        stage("Samosa"){
            steps {
                dir("simple-java-maven-app") {brew install maven}
            }
        }
        stage("Pakoda"){
            steps {
                dir("simple-java-maven-app"){maven -version}
            }
        }
    }
}