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
        // Removed the Test stage since no tests are detected
    }
}
