pipeline {
    agent { label 'master' } 
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python3 --version'
                sh 'python3 hello.py'
            }
        }
    }
}
