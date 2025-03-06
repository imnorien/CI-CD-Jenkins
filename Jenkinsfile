pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-username/Jenkins-CICD.git'
            }
        }
        stage('Build') {
            steps {
                sh 'python app.py'
            }
        }
        stage('Test') {
            steps {
                sh 'pytest test_app.py'
            }
        }
    }
}
