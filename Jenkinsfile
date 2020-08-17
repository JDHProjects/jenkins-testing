pipeline {
    agent {node {label 'ubuntu-server-20.04.1'}}
    stages {
        stage('run hello.py') { 
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
