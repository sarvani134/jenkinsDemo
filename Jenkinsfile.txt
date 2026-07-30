pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac jenkinsDemo\\SampleProgram.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java jenkinsDemo.SampleProgram'
            }
        }
    }
}