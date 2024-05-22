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
                echo "yello....."
            }
        }


    }
}