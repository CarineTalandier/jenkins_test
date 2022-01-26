pipeline {
    agent any

    stages {
        stage('NPM build') {
            steps{
                bat 'npm install'
                bat 'npm start'
            }
        }
    }
}
