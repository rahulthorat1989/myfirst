pipeline {
    agent any

    stages {
        stage('Install Docker') {
            steps {
                sh 'sudo yum install docker'
            }
        }
        stage('Start Docker service') {
            steps {
                sh 'sudo systemctl start docker'
            }
        }
        stage('show images') {
            steps {
                sh 'docker images
            }            
        }     
            stages('pull hello-world) {
                       steps {
                           sh 'sudo docker pull hello-world'
            }
        }
    }
}
