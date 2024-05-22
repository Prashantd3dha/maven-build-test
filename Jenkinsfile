pipeline {
    agent any
    tools{
        maven "Maven 3.9.6"
    }
    stages {
        stage('Build') {
            steps {
                sh "mvn clean package"
            }
        }
        stage('Test') {
            steps {
                sh "cd target"
                sh "java -jar maven-build-test-1.0-SNAPSHOT.jar"
            }
        }


    }
}
