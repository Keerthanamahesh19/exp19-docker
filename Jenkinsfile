pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t my-python-app .'
            }
        }

        stage('Run Container') {
            steps {
                bat 'docker run my-python-app'
            }
        }
    }
}
