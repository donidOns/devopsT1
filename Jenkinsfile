pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/donidOns/devopsT1.git'
            }
        }
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-app .'
            }
        }
        stage('Run Container') {
            steps {
                sh 'docker run -d -p 8080:80 my-app'
            }
        }
    }
}
