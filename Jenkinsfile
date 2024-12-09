pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac SquareCalculator.java'
            }
        }
        stage('Test') {
            steps {
                sh 'java SquareCalculator'
            }
        }
    }
}
