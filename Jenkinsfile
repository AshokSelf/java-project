pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
                script(

                    gitChecout(
                        branch: "main"
                        url: "https://github.com/AshokSelf/java-project.git"
                    )
                )
                
            }
        }
    }
}
