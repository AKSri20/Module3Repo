pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application.'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application.'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Deploying the application.'
            }
        }
    }
    post {
        success {
            echo 'Build successful'
        }
        failure {
            echo 'Build failed'
        }
    }
}
