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
        stage {
            steps {
                sh "mvn clean package"

            }
        }
    }
}
