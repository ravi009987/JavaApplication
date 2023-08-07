pipeline{
    agent any
    stages{
        stage('git  checkout'){
            steps{
               git branch: 'main', url: 'https://github.com/ravi009987/JavaApplication.git'

            }
        }
        stage('unit test:maven'){
             steps{
                  sh 'mvn test'
             }
        }
        stage('integartion test'){
            steps{
                sh 'mvn test'
            }
        }
    }
}








