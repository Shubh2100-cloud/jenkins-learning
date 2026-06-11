pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat '"C:\\Users\\aishj\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pip install pytest'
            }
        }

        stage('Run Tests') {
            steps {
                bat '"C:\\Users\\aishj\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" -m pytest tests'
            }
        }
    }
}
