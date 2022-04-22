pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'lsb_release -a'
                sh 'pwd'
            }
        }
    }
}
