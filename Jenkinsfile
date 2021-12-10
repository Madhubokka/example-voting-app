pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                sh 'cd /var/lib/jenkins/workspace/Hounslow'
                sh 'll'
                sh 'docker-compose up'
            }
        }
        stage('Test') {
            steps {
                sh  'docker version'
            
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
