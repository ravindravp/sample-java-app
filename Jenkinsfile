@Library('jenkins-shared-libraries') _

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    checkout() // Calls the shared library function
                }
            }
        }
        stage('Build') {
            steps {
                script {
                    build() // Calls the shared library function
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    test() // Calls the shared library function
                }
            }
        }
    }
}
