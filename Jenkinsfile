pipeline {
    agent any

    stages {
        stage('Environment') {
            steps {
                sh 'whoami'
                sh 'pwd'
                sh 'terraform version'
                sh 'aws --version'
            }
        }
    }
}
