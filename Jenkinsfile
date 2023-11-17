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
                // In the case of a static HTML website, there is no actual build step.
                // You might have additional build steps for minification, compression, etc.
            }
        }

        stage('Deploy') {
            steps {
                // Assuming your web server is configured to serve files from /var/www/html/
                script {
                    sh "cp -r * https://github.com/Devansh0911/travelbooking"
                }
            }
        }
    }

    post {
        success {
            echo 'Deployment succeeded!'
            // Add additional post-deployment steps or notifications here
        }
    }
}
