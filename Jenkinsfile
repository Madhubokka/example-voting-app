pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                sh 'pwd'
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
