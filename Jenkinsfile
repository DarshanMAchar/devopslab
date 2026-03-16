pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: "https://github.com/username/repository.git", branch: "main"
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 script.py'
            }
        }

    }
}
