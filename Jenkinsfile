pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh '''
                    echo "Building Docker image..."
                '''
            }
        }

        stage('Run New Container') {
            steps {
                sh '''
                    echo "Running new container..."
                    echo "Container started successfully."
                '''
            }
        }
    }
}
