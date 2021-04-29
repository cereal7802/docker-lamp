pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'ls -lash docker-lamp'
                sh 'docker build -t lamp-image docker-lamp/.'
            }
        }
    }
}
