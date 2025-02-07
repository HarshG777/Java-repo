pipeline {
    agent any

    stages {
        stage('Complie stage') {
            steps {
                bat 'javac hello.java'
            }
        }
        stage('eexecution stage') {
            steps {
                bat 'java hello'
            }
        }
    }
}
