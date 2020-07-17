pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                ls
                pwd
                whoami
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
