pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('src/main/java') {
                    bat 'javac Account.java'
                }
            }
        }
       stage('Test') {
    dir('src/test/java') {
        bat 'java -cp .;junit-4.12.jar;hamcrest-core-1.3.jar org.junit.runner.JUnitCore AccountTest'
    }
}

        }
    }
}
