pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                docker build -t gh .
            }
        }
    }
}
