pipeline {
    agent any
    environment {
        PATH = "$HOME/Desktop/flutter_projects/flutter/bin:${env.PATH}"
    }
    stages{
        stage('flutter test'){
            steps{
                sh 'flutter test'
            }
        }
    }
}