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
                    // Adjust the deployment command based on your web server and file path
                    sh 'cp -r * C:\inetpub\wwwroot
                }
            }
        }
    }
}
