pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Add build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                // Add test commands here
            }
        }
    }
    post {
        success {
            echo 'Build and tests succeeded!'
        }
        failure {
            echo 'Build or tests failed.'
        }
    }
