pipeline {
    agent any
    stages {
        stage('Install Dependencies'){
            steps {
                sh 'npm install'
            }
        }
        stage('Run tests') {
            steps {
                sh 'npm run'
            }
        }
    }
}