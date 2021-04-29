pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'ls -lash '
                sh 'docker build -t lamp-image .'
            }
        }
    }
}
