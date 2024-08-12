pipeline {
    agent any
 
    stages {
        // Stage 1: Initialize
        stage('Initialize') {
            steps {
                echo 'Initializing the pipeline...'
            }
        }
 
        // Stage 2: Build
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
 
        // Stage 3: Deploy
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
 
    post {
        always {
            echo 'Pipeline completed!'
        }
    }
}
