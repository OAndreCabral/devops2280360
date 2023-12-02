pipeline{
    agent any
    tools {
        nodejs "node" 
    }
    stages {
        stage("Stage 1"){
            steps{
                sh "docker compose up -d"
                echo "Pipeline Usando Jenkinsfile"
            }
        }
        stage("Stage 2"){
            steps{
                sh "npm i"
                echo "Pipeline Usando Jenkinsfile"
            }
        }
        stage("Stage 3"){
            steps{
                sh "npm run test:ci"
                echo "Pipeline Usando Jenkinsfile"
            }
        }
    }
}

