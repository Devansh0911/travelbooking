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
                    // You might need to adjust this based on your web server configuration
                    bat 'xcopy /s /y .\\* C:\Users\HP-PC\Desktop\Travel Booking'
                }
            }
        }
    }
}
