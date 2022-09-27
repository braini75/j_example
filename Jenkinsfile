pipeline {
    agent any
    stages {
        stage('build') {
            agent {
                docker {
                    image 'node:16.13.1-alpine' 
                }
            }
            steps {
                sh 'node --version'
            }
        }
        stage('Test'){
            steps {
                echo "This is Test-Stage"
            }
        }       
    }
}
