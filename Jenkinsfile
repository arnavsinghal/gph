pipeline {
    agent {
        docker { image 'node' }
    }
    stages {
        stage('Test') {
            steps {
               sh 'docker build -t gh .'
            }
        }
    }
}
