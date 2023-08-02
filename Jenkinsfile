pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
               script{
                git branch: 'main', url: 'https://github.com/ravi009987/JavaApplication.git'
                }
            }
        }
    }
}