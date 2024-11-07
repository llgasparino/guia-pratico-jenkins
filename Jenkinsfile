pipeline {
        agent any
        
        stages {
            stage('Build Docker Image'){
                steps{
                    echo 'Executando o comando Docker Build'
                }
            }
            stage('Push Docker Image'){
                steps{
                    echo 'Executando o comando Docker Push'
                }
            }
            stage('Deploy no k8s'){
                steps{
                    echo 'Executando o comando kubectl apply'
                }
            }
        }
    }