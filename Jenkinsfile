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
                
                sh 'java hello'
                
            }
        }
    }
}
