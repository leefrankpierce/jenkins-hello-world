pipeline {
    agent { 
        docker {
            image 'node:7-alpine' 
            label 'master'
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
