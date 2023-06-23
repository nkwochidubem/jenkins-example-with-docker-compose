pipeline {
    agent any 
    stages {
        stage "check tooling" {
            steps {
                sh  '''
                docker version
                docker info
                docker compose version
                curl --version

                '''
            }
        }
    }
}  