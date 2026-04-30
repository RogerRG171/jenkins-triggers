pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                sh 'echo "Build complete."'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "Testing..."'
            }
        }
    }
    post{
        success{
            sh 'echo "Success..."'
        }
    }
}