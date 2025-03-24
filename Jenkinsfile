pipeline {
    agent any
    tools {
        nodejs 'nodejs' // Ensure this matches the name you gave the NodeJS installation
    }
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'npm install'
                }
            }
        }
    }
}
