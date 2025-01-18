pipeline {
    agent any
    stages {
        stage('Check Environment') {
            steps {
                echo 'Checking environment variables...'
                bat 'echo PATH=%PATH%'
            }
        }
        stage('Build') {
            steps {
                echo 'Simulating build...'
                bat 'echo Build step running...'
            }
        }
    }
}
