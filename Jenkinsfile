pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment steps here
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Performing cleanup...'
                // Add your cleanup steps here
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
            // Add actions to perform on success
        }
        failure {
            echo 'Pipeline failed!'
            // Add actions to perform on failure
        }
    }
}
