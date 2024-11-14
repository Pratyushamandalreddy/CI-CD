pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "Build"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "Test"
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "Deliver"
                '''
            }
        }
        stage('End') {
            steps {
                echo 'End'
            }
        }
       
        
    }
}
