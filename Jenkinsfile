@Library('jenkins-shared-libraries') _

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    checkout()
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    build()
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    test()
                }
            }
        }
    }
}
