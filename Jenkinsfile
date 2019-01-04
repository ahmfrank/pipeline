pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/bin/mvn package"
            }
        }
    }
}
