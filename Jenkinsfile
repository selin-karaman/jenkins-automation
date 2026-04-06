pipeline {
    agent any 

    stages {
        stage('Initialize') {
            steps {
                echo 'Testing Jenkins with internal Docker CLI...'
            }
        }
        stage('Environment Check') {
            steps {
                sh 'docker --version'
                sh 'whoami'
            }
        }
    }
}