pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('C:\\Users\\amirdi\\IdeaProjects\\UnitTest') {
                    bat 'mvn compile' // Compile source code using Maven
                }
            }
        }
        stage('Test') {
            steps {
                dir('C:\\Users\\amirdi\\IdeaProjects\\UnitTest') {
                    bat 'mvn test' // Run tests using Maven
                }
            }
        }
    }
}

