pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Sample.java'   // Use 'sh' instead of 'bat' for Linux
            }
        }
        stage('Run') {
            steps {
                bat 'java Sample'
            } 
        }
    }
}
