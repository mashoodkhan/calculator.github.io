pipeline {
    agent {
        docker {
            image 'node:14'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building Calculator...'
                // Add your Node.js build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Testing  Calculator...'
                // Add your Node.js test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Calculator...'
                // Add your deployment steps here
            }
        }
    }
}
