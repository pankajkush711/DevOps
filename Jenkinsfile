pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/pankajkush711/DevOps.git',
                    credentialsId: 'github-pat'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Example: sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'mvn test'
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
