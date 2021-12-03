pipeline {
    agent any

    stages {
        stage('SCM Checkout') {
            git 'https://github.com/Saurav66/HTML-Template'
        }
        stage('Email Notification') {
            mail bcc: '', body: 'Hi', cc: '', from: '', replyTo: '', subject: 'Jenkins jobs', to: 'saruravkumar3897@gmail.com'   
        }
    }
}
