pipeline {
    agent any
    environment {
        PATH = "/usr/share/maven/bin:$PATH"
    }
    stages {
        stage("Maven build") {
            steps {
                sh "mvn clean package"
            }
        }
    }
}
