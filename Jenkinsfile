pipeline {
    agent any

    stages {
        stage('Checkout Git Repository') {
            steps {
                dir('source-code') {
                    checkout scm
                }
            }
        }

        stage('Verify Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
