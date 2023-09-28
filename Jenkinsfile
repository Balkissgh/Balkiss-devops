pipeline {
    agent any
    stages {
        stage('Checkout Git') {
            steps {
                script {
                    git branch: 'main',
                      url: 'https://github.com/Balkissgh/Balkiss-devops.com',
                      credentialsId: 'devops-classe-git' 

                }
            }
        }
    }
}

