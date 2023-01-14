pipeline {
    agent any
    tools {
    maven 'maven'
    }
    stages {
        stage ('Clone') {
            steps {
                git 'https://github.com/4ndrevv/gilded-rose-jenkin.git'
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