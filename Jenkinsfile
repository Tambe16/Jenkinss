pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Tambe16/Jenkinss.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Execute') {
            steps {
                sh 'java hello'
            }
        }
    }
}
