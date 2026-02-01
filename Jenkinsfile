pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building project...'
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
