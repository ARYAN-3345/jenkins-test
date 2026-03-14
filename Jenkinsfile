pipeline {
    agent any

    stages {

        stage('Check Version'){
            steps{
                bat 'python --version'
            }
        }
        
        stage('Run Python') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
