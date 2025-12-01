pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-static-site .'
            }
        }
        stage('Run Container') {
            steps {
                sh 'docker run -d -p 8080:80 --name static-site my-static-site'
            }
        }
    }
}
