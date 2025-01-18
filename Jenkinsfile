pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning the repository...'
                // No explicit Git commands required if using Pipeline SCM configuration
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Replace this with your actual build command
                bat 'echo Simulating build step...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace this with your actual test command
                bat 'echo Simulating test step...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Replace this with your actual deploy command
                bat 'echo Simulating deploy step...'
            }
        }
    }
    post {
        always {
            echo 'Cleaning up workspace...'
            deleteDir() // Clean the workspace
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check the logs for details.'
        }
    }
}
