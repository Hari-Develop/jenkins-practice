pipeline {
    agent {
        node {
            label 'workstation'
        } 
    }
    stages {
        stage('Build') {
            steps {
                // Add build steps here
                sh 'echo "Building..."'
            }
        }
        stage('Test') {
            steps {
                // Add test steps here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Add deploy steps here
                sh 'echo "Deploying..."'
            }
        }
        stage('release') {
            steps {
                // Add release steps here
                sh 'echo "releasing the application..."'
            }
        }
        
    }
}
