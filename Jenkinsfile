pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Everybody Lies !'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}