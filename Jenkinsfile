pipeline {
    agent any

    stages {

        stage('Show Workspace') {
            steps {
                echo 'Current folder:'
                bat 'cd'
                echo 'Files in workspace:'
                bat 'dir'
            }
        }

    }
}
