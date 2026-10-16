pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Date') {
            steps {
                sh 'date'
            }
        }
    }
}
