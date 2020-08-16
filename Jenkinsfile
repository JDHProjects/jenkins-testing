pipeline {
    agent {node {label 'ubuntu-server-20.04.1'}}
    stages {
        stage('install python') { 
            steps {
                sh 'apt update'
                sh 'apt install python3.8'
                sh 'python --version'
            }
        }
        stage('run hello.py') { 
            steps {
                sh 'python hello.py'
            }
        }
    }
}
