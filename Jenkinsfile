pipeline {
    agent any
    stages {
        stage('Echo Hello World') {
            steps {
                echo 'Hello, Jenkins!'
            }
        }
        stage('Check System Info') {
            steps {
                sh 'uname -a'
                sh 'whoami'
            }
        }
        stage('Echo Hello DD') {
            steps {
                echo 'Hello, DD!'
            }
        }
        stage('List Files in Workspace') {
            steps {
                sh 'ls -lah'
            }
        }
    }
}
