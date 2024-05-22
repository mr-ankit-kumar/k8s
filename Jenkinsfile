pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'ls configure-pods/'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        stage('Print Message') {
            steps {
                script {
                    def message = "Hello, this is a custom message from your Jenkins pipeline!"
                    echo message
                }
            }
        }
    }
}
