pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: "https://github.com/DarshanMAchar/devopslab.git", branch: "main"
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 script.py'
            }
        }

    }
}
