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
                    // Replace '/path/to/web/server/directory' with the actual deployment path on your web server
                    def deployPath = 'https://github.com/Devansh0911/travelbooking/tree/main'

                    // Create the deployment directory if it doesn't exist
                    sh "mkdir -p ${deployPath}"

                    // Copy all files to the deployment directory
                    sh "cp -r * ${deployPath}"
                }
            }
        }
    }
}
