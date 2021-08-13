pipeline {
    agent any

    stages {
        stage('checking version') {
            steps {
                bat 'javac -version'
            }
        }
        
        stage('compile') {
            steps {
                bat 'javac Main.java'
            }
        
        }
    }
}
