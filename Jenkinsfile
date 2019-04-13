pipeline {
    agent { 
        docker {
            image 'node:centos' 
            label 'docker'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
