pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                docker.build("getintodevops/hellonode")
            }
        }
    }
}
