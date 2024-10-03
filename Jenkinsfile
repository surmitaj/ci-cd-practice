pipeline {
    agent any
    stages {
        stage('Install Dependencies'){
            steps {
                bat 'npm install'
            }
        }
        stage('Run tests') {
            steps {
                bat 'npm run'
            }
        }
    }
}
