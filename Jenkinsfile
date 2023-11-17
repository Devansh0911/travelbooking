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
                    // Create the target directory in the Jenkins workspace
                    sh 'mkdir -p $WORKSPACE/travelbooking'

                    // Deploy the website
                    sh 'cp -r * $WORKSPACE/travelbooking'
                }
            }
        }
    }
}
