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
                echo 'Building..'
                // Add your build steps here
            }
        }

        stage('Archive') {
            steps {
                archiveArtifacts '**/*'
            }
        }
    }

    post {
        success {
            echo 'Archiving artifacts...'
        }
    }
}
