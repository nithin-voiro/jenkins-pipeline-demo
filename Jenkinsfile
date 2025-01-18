pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning Repository...'
                // Jenkins will automatically clone the repo
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh './build.sh' // Example build script
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh './test.sh' // Example test script
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh './deploy.sh' // Example deploy script
            }
        }
    }
    post {
        always {
            echo 'Pipeline execution finished.'
        }
    }
}
