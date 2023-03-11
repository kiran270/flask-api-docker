pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'docker build -t flask-api-docker:latest .'
            }
        }
    }
}
