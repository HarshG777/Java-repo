pipeline {
    agent { label 'agent1' }
 
    stages {
        stage('Compile') {
            steps {
                
                sh 'javac hello.java'
                echo "Compilation successful."
                
            }
        }
        stage('Run') {
            steps {
                dir('java_file') {
                    sh 'java Hello'
                }
            }
        }
    }
}
