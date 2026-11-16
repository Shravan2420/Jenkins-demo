
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Compiling Java program'
                bat 'javac Hello.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Java program'
                bat 'java Hello'
            }
        }
    }
}
