pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/home/osboxes/apache-maven-3.5.2/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/home/osboxes/apache-maven-3.5.2/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/home/osboxes/apache-maven-3.5.2/bin/mvn package"
            }
        }
    }
}
