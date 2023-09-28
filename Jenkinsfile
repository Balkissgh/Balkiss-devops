pipeline {
    agent any
    stages {
        stage('Checkout Git') {
            steps {
                script {
                    git branch: 'main',
                      url: 'https://github.com/Balkissgh/Balkiss-devops.git', 
                      credentialsId: 'devops-classe-git'    

                }
            }
        }
        stage('Afficher date systeme') {  
            steps {
            sh 'date'
                 }
    }
}
}

