pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                bash 'go version'
            }
        }
    }
}
