pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh whoami

            }
        }

        stage('Test') {
            steps {
                sh df -h
                sh touch team6
            }
        }

        stage(backup){
            steps{
                sh pwd
                sh du -h
            }
        }
    }
}