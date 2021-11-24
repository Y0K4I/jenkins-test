pipeline {
    agent any
    stages {
        stage('Update packages & build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}