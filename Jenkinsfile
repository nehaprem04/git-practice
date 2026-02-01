pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project version 2'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }

    }
}
