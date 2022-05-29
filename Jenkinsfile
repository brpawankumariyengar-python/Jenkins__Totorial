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
        stage("Pakoda"){
            steps {
                dir("simple-java-maven-app"){sh 'mvn -v'}
                dir("simple-java-maven-app"){'mvn -v'}
            }
        }
    }
