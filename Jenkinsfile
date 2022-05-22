pipeline {
    agent any
    stages {
        stage("Clean Up"){
            steps {
                deleteDir()
            }
        }
        stage("Clone Repo"){
            steps {
                sh "git clone https://github.com/jenkins-docs/simple-java-maven-app.git"
            }
        }
        stage("Build"){
            steps {
                dir("simple-java-maven-app") 
            }
            steps{
                brew install maven
            }
        }
        stage("Test"){
            steps {
                dir("simple-java-maven-app")
            }
            steps{
                maven -version
            }
        }
    }
}