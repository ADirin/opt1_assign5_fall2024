pipeline {
    agent any

    stages {
    stage('Build') {
    steps {
        dir('/absolute/path/to/workspace/Users/amirdi/ideaProjects/UnitTest/src/main/java') {
            bat 'mvn compile' // Compile source code using Maven
        }
    }
}

        stage('Test') {
            steps {
                dir('/absolute/path/to/workspace/Users/amirdi/ideaProjects/UnitTest/src/main/java') {
                    bat 'mvn test' // Run tests using Maven
                }
            }
        }
    }
}

