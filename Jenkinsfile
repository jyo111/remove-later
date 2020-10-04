pipeline {
    agent any
    environment {
        PATH = "/usr/share/maven:$PATH"
    }
    stages {
        stage('Git checkout') {
            steps {
                echo 'GGGGGGGGGGGGGGGGGGGGGG'
            }
        }
        stage('maven build') {
            steps {
                sh "mvn clean package"

            }
        }
    }
}
