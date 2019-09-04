pipeline {
    agent any

    stages {
        stage('Code Checkout') {
            steps {
                echo 'Code Checkout..'
                cleanWs()
                checkout scm
                sh """
                    pwd
                    ls -ltr
                """
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}