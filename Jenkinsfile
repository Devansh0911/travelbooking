pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Check out the source code from your version control system (e.g., Git)
                // git 'your_repository_url_here'
            }
        }

        stage('Build') {
            steps {
                // In this case, there's no compilation or build process, as it's a static HTML website
            }
        }

        stage('Test') {
            steps {
                // You can add testing steps here if needed
            }
        }

        stage('Deploy') {
            steps {
                // Replace these placeholder values with your actual deployment configuration
                // sh 'rsync -avz --delete path/to/your/website/* user@your_server:/path/to/deploy'
            }
        }
    }

   
}
