pipeline {
    agent any
    stages {
        stage("Stage 1"){
            steps {
                echo "This is stage 1"
            }
        }
        stage("Stage 2"){
            steps {
                echo "This is stage 2"
            }
        }
        stage("Stage 3"){
            steps {
                echo "This is stage 3"
                }
            }
        stage("Stage 4"){
            steps {
                sh "mkdir Tota"
                }
            }
        stage("Stage 5"){
            steps {
                sh "python3 --version"
                    }
        }
        stage("Stage Final"){
            steps {
                sh "pwd"
                    }
            }
        }
    }
