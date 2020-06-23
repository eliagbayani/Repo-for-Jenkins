pipeline {
    agent { docker { image 'php:5.6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}