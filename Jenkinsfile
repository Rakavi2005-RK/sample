pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                sh 'javac sample.java'
            }
        }
        stage("Run") {
            steps {
                sh 'java sample'
            }
        }
    }
}
