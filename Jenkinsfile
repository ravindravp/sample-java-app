@Library('jenkins-shared-libraries') _
pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    customCheckout()
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
        stage('Deploy') {
            steps {
                script {
                    deploy()
                }
            }
        }
    }
}
