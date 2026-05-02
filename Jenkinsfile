pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                // sh 'npm install' // Aktifkan jika Jenkins Anda sudah ada NodeJS
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
