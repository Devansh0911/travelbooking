pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               
                echo 'Building the application...'
            
            }
        }

        stage('Test') {
            steps {
              
                echo 'Running tests...'
             
            }
        }

        stage('Deploy') {
            steps {
                
                echo 'Deploying the application...'
               
            }
        }
    }

    post {
        success {
          
            echo 'Pipeline completed successfully!'
        }

        failure {
           
            echo 'Pipeline failed. Deployment unsuccessful.'
        }
    }
}
