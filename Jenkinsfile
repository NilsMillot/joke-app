pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "npm install"
                sh "npm run build"
                sh "npm test"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}