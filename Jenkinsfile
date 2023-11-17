pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the source code from your version control system (e.g., Git)
                git 'your_repository_url_here'
            }
        }

        stage('Build') {
            steps {
                // In this case, there's no compilation or build process, as it's a static HTML website
            }
        }

        stage('Deploy') {
            steps {
                // Copy the HTML files to your web server
            
            }
        }
    }

    post {
        success {
            // This block runs if the pipeline is successful
        
        }

        failure {
            // This block runs if the pipeline fails
          
        }
    }
}
