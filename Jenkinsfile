pipeline {
    agent any

    stages {
     stages {
        stage('Build') {
            steps {
                dir('/path/to/workspace/src/main/java') {
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

