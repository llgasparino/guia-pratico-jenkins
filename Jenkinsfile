pipeline {
        agent any
        
        stages {
            stage('Build Docker Image'){
                steps{
                    sh 'Executando o comando Docker Build'
                }
            }
            stage('Push Docker Image'){
                steps{
                    sh 'Executando o comando Docker Push'
                }
            }
            stage('Deploy no k8s'){
                steps{
                    sh 'Executando o comando kubectl apply'
                }
            }
        }
    }