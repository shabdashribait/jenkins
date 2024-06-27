pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build commands here, e.g., compile code
                 sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here, e.g., run unit tests
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy commands here, e.g., deploy to a server
                sh 'mvn deploy'
            }
        }
    }
}
