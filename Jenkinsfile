pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands, like:
                // sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Deployment commands here
            }
        }
    }
}
