@Library("my-shared-library") _
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
                mavenBuild()
            }
        }
        stage('deploy') {
            steps {
               deploy()
            }
        }
    }
}
