pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Nandy2907/jenkins.git'
            }
        }
        stage('Run Python Script') {
            steps {
                bat 'python timestamp_printer.py'
            }
        }
    }
}
