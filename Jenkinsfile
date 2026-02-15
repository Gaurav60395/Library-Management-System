pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    // This will run the Maven build
                    sh 'mvn clean package'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Placeholder for running tests
                    // sh 'mvn test'
                }
            }
        }
    }
}
