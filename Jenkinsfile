pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Explicitly clones the code using the job's SCM configuration
                checkout scm
            }    
        }
        stage('Test') {
            steps {
              echo "Test Stage"
            }
        }
        // Additional stages
    }
    post {
        always {
            echo "This is Jenkinsfile"
        }
    }
}
