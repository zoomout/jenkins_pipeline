pipeline {
    agent any

    stages {
        stage('mock server test') {
            steps {
                git url: 'https://github.com/zoomout/mockserver'
                sh 'mvn clean install'
            }
        }
    }
}