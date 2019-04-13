pipeline {
    agent { 
        docker { 
            image 'node:7-alpine' 
            label 'build'
        }
    }
    stages {
        stage('Test') {
            agent { label 'build' }
            steps {
                sh 'node --version'
            }
        }
    }
}
