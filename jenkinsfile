
pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Compiling Java program'
                bat 'javac TextHello.java'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Java program'
                bat 'java TextHello'
            }
        }
    }
}
