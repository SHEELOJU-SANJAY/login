pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat '''
                    echo Building Docker image...
                '''
            }
        }

        stage('Run New Container') {
            steps {
                bat '''
                    echo Running new container...
                    echo Container started successfully.
                '''
            }
        }
    }
}
