pipeline{
    //agent any
    agent {label 'worker'}
    stages{
        stage('Git Pull'){
            steps{
                sh "echo hello"
                sh "echo hi again"
            }
        }
        stage('Build and Push'){
            steps{
                sh "echo hello"
            }
        }
        stage('Deployment'){
            steps{
                sh "echo deployment"
            }
        }      
    }
}
