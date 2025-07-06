pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Building the project..."
            }
        }
        stage('test') {
            steps {
                echo "Running tests..."
                sh 'java --version'
            }
        }
        stage('deploy') {
            steps {
                echo "Deploying the project..."
            }
        }
    }
}