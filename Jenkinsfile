pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'java -version'
            }
        }
        stage('Test') { 
            steps {
                sh 'whoami'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'jenkins --version' 
            }
        }
    }
}
