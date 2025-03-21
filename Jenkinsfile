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
                echo 'docker build'
            }
        }
        stage('Run Container') {
            steps {
                echo 'deploy'
            }
        }
    }
}
