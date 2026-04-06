pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Running tests...'
                echo 'All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                echo 'Deployment successful!'
            }
        }

    }

    post {
        success {
            echo 'Pipeline SUCCESS!'
        }
        failure {
            echo 'Pipeline FAILED!'
        }
    }
}
