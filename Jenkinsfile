pipeline {
    agent any
    stages {
        stage('jonas') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl'
            }
        }
        stage('parallel'){
        parallel{
        stage('prosper') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl'
            }
        }
        stage('erica m') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl'
            }
        }
        }
        }
        stage('bill') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl'
            }
        }
         stage('gilbert') {
            steps {
                sh 'ps -ef'
                sh 'sudo systemctl'
            }
        }
    }
}