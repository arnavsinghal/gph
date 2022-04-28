pipeline {
    agent {
        docker { image 'node' }
    }
    stages {
        stage('Test') {
            steps {
               docker build -t gh .
            }
        }
    }
}
