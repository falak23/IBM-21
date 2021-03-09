pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps{
                git 'pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps{
                git 'https://github.com/falak23/IBM-21'
            }
        }
        stage('Compile') {
            steps{
                bat 'javac Demo.java'
            }
        }
    }
    post {
        failure {
            mail bcc: '', body: "$BUILD_NUMBER", subject: "$JOB_NAME", to: 'falak.mujeeb@gmail.com'
        }
        success {
            mail bcc: '', body: "$BUILD_NUMBER", subject: "$JOB_NAME", to: 'falak.mujeeb@gmail.com'
        }      
    }
}'
            }
        }
        stage('Compile') {
            steps{
                bat 'javac Demo.java'
            }
        }
    }
    post {
        failure {
            mail bcc: '', body: "$BUILD_NUMBER", subject: "$JOB_NAME", to: 'falak.mujeeb@gmail.com'
        }
        success {
            mail bcc: '', body: "$BUILD_NUMBER", subject: "$JOB_NAME", to: 'falak.mujeeb@gmail.com'
        }      
    }
}