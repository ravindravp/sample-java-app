@Library('jenkins-shared-libraries') _

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
              checkout scm
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
