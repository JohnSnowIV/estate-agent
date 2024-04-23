
pipeline {
    agent any
    stages {
        stage ('Build Docker Image') {
            steps {
                script {
                    bat 'docker build -t shippingcontainer1/fe-devops .'
                }
            }
        }
    }
}
