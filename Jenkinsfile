pipeline {
    agent any
    
    stages {
        stage('Print Build Number') {
            steps {
                script {
                    echo "Build Number: ${BUILD_NUMBER}"
                }
            }
        }
        
        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
