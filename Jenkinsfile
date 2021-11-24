pipeline {
    agent any
    stages {
        stage('Pull project') {
            steps {
                sh 'git pull origin master'
            }
        }
        stage('Update packages & build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}