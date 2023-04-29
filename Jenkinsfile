pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building"'
            }
        }
        stage('Test') {
            steps {
                python hello.py
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying"'
            }
        }
    }
}

