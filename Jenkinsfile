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

       
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Triggering deployment...'
            // Add additional deployment steps or notifications here
        }
    }
}
