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
                    bat 'xcopy /s /y .\\* C:\\path\\to\\web\\server\\directory'
                }
            }
        }
    }
}
