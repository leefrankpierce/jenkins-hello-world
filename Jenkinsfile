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
                sh 'uname -a'
            }
        }
    }
}
