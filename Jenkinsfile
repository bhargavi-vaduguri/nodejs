pipeline {
    agent { label 'jdk11-mvn3.6.3' }
    stages {
        stage('scm') {
            steps {
                git 'https://github.com/bhargavi-vaduguri/nodejs.git'
            }
        }
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}


    