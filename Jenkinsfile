pipeline {
    agent any 
    stages {
        stage('Build Docker Image') {
            steps {
                echo 'Build, Tag and Push the Docker Image into Docker Hub'
                sh '''
                      docker build -t myrepo:argodemo .
                   '''
            }
        }
    }
}
