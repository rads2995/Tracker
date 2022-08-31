pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Docker image...'
                sh "docker build -t tracker ."
            }
        }
        stage('Test') {
            steps {
                echo 'No testing has been implemented..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'No deployment has been implemented....'
            }
        }
    }
}