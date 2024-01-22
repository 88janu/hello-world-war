pipeline {
    agent {label 'slave1'}
    stages {
        stage('checkout') {
            steps {
                gitHelloWorld()
            }
        }
        stage('build') {
            steps {
                mavenbuild()
            }
        }
        stage('deploy') {
            steps {
               deloy()
            }
        }
    }
}
