@Library('jenkins_shared_lib') _

pipeline {
    agent any
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }

    stages {
        stage('Git checkout') {
            steps {
                gitCheckout(
                    branch: 'main',
                    url: 'https://github.com/AshokSelf/java-project.git'
                )
            }
        }
        stage('Unit Test Maven') {
            steps {
                mvnTest()
            }
        }
    }
}