pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Replace the following command with your deployment logic
                    echo 'Deploying the website to the web server...'
                    
                    sh 'cp -r * /var/www/html'
                }
            }
        }
    }
}
