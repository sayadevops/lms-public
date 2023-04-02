pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
                echo 'Building..'
                dir('webapp') {
                     sh 'npm install'
                     sh 'npm run build'
                }
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
