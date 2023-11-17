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
                    // Create the target directory if it doesn't exist
                    sh 'mkdir -p /travelbooking'

                    // Deploy the website
                    sh 'cp -r * /travelbooking'
                }
            }
        }
    }
}
