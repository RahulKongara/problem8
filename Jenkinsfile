pipeline{
    agent any 
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'docker build -t my-nodejs-app-csed .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Running Tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying application...'
                }
            }
        }
        stage('Release') {
            steps {
                script {
                    echo 'Releasing application...'
                }
            }
        }
    }
}