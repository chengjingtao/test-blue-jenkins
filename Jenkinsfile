pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                sh "pwd"
                sh "ls -l"
                git 'https://github.com/chengjingtao/LoveFavorites.git'
                sh "pwd"
                sh "ls -l"
            }
        }
        stage('Build') {
            steps {
                sh "pwd"
                sh "ls -l"
                input "beging to build now !!!!??"
                sh "make build"
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

