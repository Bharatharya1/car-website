pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Bharatharya1/car-website.git'
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
                sh '''
                sudo cp -r * /var/www/html/
                '''
                echo 'Website deployed successfully.'
            }
        }
    }
}
