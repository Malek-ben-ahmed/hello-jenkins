pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Malek-ben-ahmed/hello-jenkins.git'
            }
        }

        stage('Run Application') {
            steps {
                sh 'python3 main.py'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'python3 test_main.py'
            }
        }
    }
}
