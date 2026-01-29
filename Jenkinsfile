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
        // Note: If tests are added in the future, consider adding a test stage here.
    }
}
