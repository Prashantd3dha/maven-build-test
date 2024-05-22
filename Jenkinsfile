pipeline {
    agent any
    tools{
        maven "Maven 3.9.6"
    }
    stages {
        stage('Build') {
            steps {
                bat "mvn clean package"
            }
        }
        stage('Test') {
            steps {
                bat "java -jar target/maven-build-test-1.0-SNAPSHOT.jar"
            }
        }


    }
}
