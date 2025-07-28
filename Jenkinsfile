pipeline {
    agent any

    stages {
        stage('w/o docker') {
            steps {
                sh 'echo "Without docker" '
                sh 'touch no-docker.txt'
            }
        }
    }