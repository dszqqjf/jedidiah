pipeline {
    agent any
    tools {
        jdk 'jdk8'
        maven 'Maven 3.3.9'
    }
    stages {
        stage('Initialize') {
            steps {
               sh '''
                    echo "PATH = ${PATH}"
                '''
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
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