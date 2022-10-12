pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "npm i -g pnpm"
                sh "pnpm install"
                sh "pnpm build"
                sh "pnpm test"
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