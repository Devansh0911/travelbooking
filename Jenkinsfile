pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Simulate a build step (replace with actual build commands)
                echo 'Compiling source code...'
                echo 'Creating executable...'
                echo 'Build successful!'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulate running tests (replace with actual test commands)
                echo 'Executing unit tests...'
                echo 'All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Simulate deployment (replace with actual deployment steps)
                echo 'Copying files to the server...'
                echo 'Restarting application server...'
                echo 'Deployment successful!'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
            // Additional actions on success (e.g., notifications, triggering other jobs)
        }

        failure {
            echo 'Pipeline failed. Deployment unsuccessful.'
            // Additional actions on failure (e.g., notifications, rollback changes)
        }
    }
}
