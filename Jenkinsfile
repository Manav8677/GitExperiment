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
                echo 'Build stage executed successfully'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage executed successfully'
            }
        }
    }
}
