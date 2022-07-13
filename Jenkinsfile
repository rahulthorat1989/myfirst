pipeline {
    agent any

    stages {
        stage('Install Docker') {
            steps {
                sh 'sudo yum install docker -y'
            }
        }
        stage('Start Docker service') {
            steps {
                sh 'sudo systemctl start docker'
            }
        }
        stage('show images') {
            steps {
                sh 'sudo docker images'
            }            
        }     
         stage('pull hello-world') {
             steps {
                 sh 'sudo docker pull hello-world'
            }
        }
    }
}
