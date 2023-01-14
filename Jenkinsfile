pipeline {
    agent any
    stages {
        stage ('Clone') {
            steps {
                git 'https://github.com/4ndrevv/docker_jenkin_web_app.git'
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