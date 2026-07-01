pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Bharatharya1/car-website.git'
            }
        }

        stage('Deploy Website') {
            steps {
                sh '''
                cp -r * /var/www/html/
                '''
            }
        }

    }
}
