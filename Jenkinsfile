#pipeline {
#    agent { docker { image 'python:3.5.1' } }
#    stages {
#        stage('build') {
#            steps {
#                sh 'python --version'
#                sh 'echo "hello world"'
#            }
#        }
#    }
#}

pipeline {
    agent any

    stages {
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
