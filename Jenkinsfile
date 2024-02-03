pipeline {
    agent {
        node {
            label 'workstation'
        } 
    }
    environment {
        // using the envirnoment varibales here
        TESTING_VERSION = "1.0.0"
        DEPLOYING_VERSION = "TESTING_VERSION"
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
                sh 'echo "Testing..${TESTING_VERSION}."'
            }
        }
        stage('Deploy') {
            steps {
                // Add deploy steps here
                sh 'echo "Deploying...${DEPLOYING_VERSION}"'
            }
        }
        stage('release') {
            steps {
                // Add release steps here
                sh 'echo "releasing the application..."'
            }
        }
        
    }
    post {
        always {
            echo "pipline is running...."
        }
        failure {
            echo "pipline is failure..."
        }
        success {
            echo "pipline is success...party..ledha..pushpa.."
        }
    }
}
