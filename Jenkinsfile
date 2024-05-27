pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('src/main/java') {
                    bat 'mvn compile' // Compile source code using Maven
                }
            }
        }
        stage('Test') {
            steps {
                dir('src/test/java') {
                    bat 'mvn test' // Run tests using Maven
                }
            }
        }
    }
}

