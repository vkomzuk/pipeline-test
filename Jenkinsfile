pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sh "ls -la"
            }
        }    
        stage('Deploy') {
            steps {
                echo 'Deployment'
                sh '''
                echo Deploy1
                echo Deploy2
                echo Deploy3
                '''
            }
        }
    }
}
