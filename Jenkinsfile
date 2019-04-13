pipeline {
    agent { 
        docker {
            image 'centos' 
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
