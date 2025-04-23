pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git credentialsId: 'b88b9edc-b71e-4370-b64f-7c75454a19a0', url: 'https://github.com/N123bhanu/Star'
            }
        }

        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies...'
                // Example: sh 'npm install' or any setup command
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Running tests...'
                // Example: sh 'npm test'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Example: sh 'npm run build'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Example: sh './deploy.sh'
            }
        }
    }
}
