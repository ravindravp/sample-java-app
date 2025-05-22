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
                    build() // Calls the build function from the shared library
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    test() // Calls the test function from the shared library
                }
            }
        }
    }
}
