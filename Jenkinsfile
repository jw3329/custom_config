pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
                sh 'pwd'
                sh 'whoami'
                sh 'docker'
                docker
                echo 'Building..'
                echo 'Changing....'
                echo 'Another Change!!!!!.....'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
