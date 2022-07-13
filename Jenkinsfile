pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'df -h'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
