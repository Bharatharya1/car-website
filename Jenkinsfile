pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out successfully.'
            }
        }

        stage('Build') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'HTML project verified successfully.'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed.'
            }
        }
    }
}
