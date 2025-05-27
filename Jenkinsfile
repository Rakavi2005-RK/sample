pipeline {
    agent any
    stages {
        stage("Compile") {
            steps {
                bat 'javac Sample.java'
            }
        }
        stage("Run") {
            steps {
                bat 'java Sample'
            }
        }
    }
}
