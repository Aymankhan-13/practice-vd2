
pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
                sh 'ls -l'
                dir ('foo') {
                    writeFile file:'dummy', text:''
                            }
                sh 'ls -l'
                sh 'pwd'
            }
        }
    }
}
