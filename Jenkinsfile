pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                sh 'javac Sample.java'
            }
        }
        stage("Run") {
            steps {
                sh 'java Sample'
            }
        }
    }
}
