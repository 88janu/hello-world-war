pipeline {
    agent slave1
    stages {
        stage('checkout') {
            steps {
                sh ''
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn clean install'
            }
        }
    }
}
