pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac SampleProgram.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java SampleProgram'
            }
        }
    }
}