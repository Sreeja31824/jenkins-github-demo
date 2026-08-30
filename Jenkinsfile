pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code is being checked out from GitHub'
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

    post {
        success {
            echo 'Jenkins Pipeline completed successfully'
        }

        failure {
            echo 'Jenkins Pipeline failed'
        }
    }
}
