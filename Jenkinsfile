pipeline {
    agent any
    environment {
        PATH = "/usr/bin/mvn:$PATH"
    }
    stages {
        stage("Maven build") {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
