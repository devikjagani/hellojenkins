pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/devikjagani/hellojenkins.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
