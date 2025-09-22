pipeline {
    agent any
    stages{
        stage('Checkout Code'){
            checkout scmGit(branches: [[name: '*/main']], 
            extensions: [], 
            userRemoteConfigs: [[credentialsId: '37fa8c5a-1f17-42ce-91b1-43814f29c41a', url: 'https://github.com/AkroutHassen/Devops-Cloud-TP']])
        }
    }
}