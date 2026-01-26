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
                    // This will run the tests (if any were added later)
                    sh 'mvn test'
                }
            }
        }
    }
}
