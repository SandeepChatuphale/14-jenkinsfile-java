pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'javac -version'
            }
        }
        
        stage('compile') {
            steps {
                bat 'javac Main.java'
            }
        }
