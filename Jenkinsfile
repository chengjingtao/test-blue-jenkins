pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                input "begin to clone?"
                git 'https://github.com/chengjingtao/LoveFavorites.git'
            }
        }
        stage('Build') {
            steps {
                input "beging to build now !!!!??"
            }
        }
        stage('Test') {
            steps {
                sh 'make test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

