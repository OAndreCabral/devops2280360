pipeline{
    agent any

    stages {
        stage("Stage 1"){
            steps{
                sh "docker compose up -d"
                echo "Pipeline Usando Jenkinsfile"
            }
        }
        stage("Stage 2"){
            steps{
                sh npm i
                echo "Pipeline Usando Jenkinsfile"
            }
        }
    }
}

