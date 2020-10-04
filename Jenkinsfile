pipeline {
    agent any
    environment {
        PATH = "/maven3/bin:$PATH"
    }
    stages {
        stage("Maven build") {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
