pipeline {
    agent { label 'master'
        docker { 
            image 'node:7-alpine' 
            label 'build'
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
