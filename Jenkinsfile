@library('my-shared-library') _
pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
                gitCheckout(
                    branch: 'main',
                    url: 'https://github.com/AshokSelf/java-project.git'
                )
            }
        }
    }
}
