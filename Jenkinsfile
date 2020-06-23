pipeline {
    agent { docker { image 'php:5.6.30' } }
    stages {
        stage('build') {
            steps {
//                sh 'php --version'
//                php --version
                sh label: '', script: 'php --version'
            }
        }
    }
}