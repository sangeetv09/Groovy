//Testing for staging pipeline//

pipeline {
    agent any   // This means run on any available Jenkins agent

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
                echo 'Deploying to staging environment...'
                
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check logs.'
        }
    }
}
