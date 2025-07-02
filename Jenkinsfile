pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/cbindushree/python-demo.git'
            }
        }
        stage('Run Python Script') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
