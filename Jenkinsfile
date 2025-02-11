pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Nandy2907/jenkins.git'
            }
        }
        stage('Compile Java Code') {
            steps {
                bat 'javac TimestampPrinter.java'
            }
        }
        stage('Run Java Program') {
            steps {
                bat 'java TimestampPrinter'
            }
        }
    }
}
