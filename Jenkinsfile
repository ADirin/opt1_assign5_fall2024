pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('absolute/path/to/workspace/Users/amirdi/ideaProjects/UnitTest') {
                    bat 'mvn compile' // Compile source code using Maven
                }
            }
        }
        stage('Test') {
            steps {
                dir('absolute/path/to/workspace/Users/amirdi/ideaProjects/UnitTest') {
                    bat 'mvn test' // Run tests using Maven
                }
            }
        }
    }
}

