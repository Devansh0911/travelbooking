pipeline {
    agent any

    stages {
        stage('Checkout SCM') {
            steps {
                // Checkout the source code from SCM (e.g., Git)
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Build the application using Maven
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                // Run tests using Maven
                sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application (Replace with your deployment steps)
                echo 'Deploying the application...'
            }
        }
    }

    post {
        success {
            // Actions to perform on success
            echo 'Pipeline completed successfully!'
            // Additional actions (e.g., notifications, triggering other jobs)
        }

        failure {
            // Actions to perform on failure
            echo 'Pipeline failed. Deployment unsuccessful.'
            // Additional actions (e.g., notifications, rollback changes)
        }
    }
}
