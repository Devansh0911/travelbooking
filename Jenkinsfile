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
                // You may have additional build steps here if needed
            }
        }

        stage('Deploy') {
            steps {
                // Assuming your website content is in the 'dist' directory
                sh "cp -r dist/* /var/www/html/"
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Triggering deployment...'
            // Add additional deployment steps or notifications here
        }
    }
}
