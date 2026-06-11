pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Code checkout done'
            }
        }

        stage('Run Python Script') {
            steps {
                bat '"C:\\Users\\AiShu\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" hello.py'
            }
        }
    }
}
