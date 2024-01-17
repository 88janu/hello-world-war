pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                sh 'https://github.com/88janu/hello-world-war.git'
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
