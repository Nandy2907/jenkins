pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Run Python Script') {
            steps {
                bat 'python timestamp_printer.py'
            }
        }
    }
}
