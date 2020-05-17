pipeline {
    agent {
        docker { image 'ecs-deploy:1.10.1' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ecs scale --help'
            }
        }
    }
}
