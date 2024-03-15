pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from your Git repository
                git 'https://github.com/AnkushPal98/Devops-Assignment-Jenkins.git'
            }
        }
        stage('Build') {
            steps {
                echo "Build stage"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy stage"
            }
        }
    }
}