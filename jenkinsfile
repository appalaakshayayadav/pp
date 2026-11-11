pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat '"C:/Users/nisha/AppData/Local/Programs/Python/Python311/python.exe" app.py'
            }
        }
    }
}