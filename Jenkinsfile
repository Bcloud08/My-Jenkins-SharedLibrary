// Import the shared library
@Library('My-Jenkins-SharedLibrary') _

// Use the functions from the shared library
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Call the 'hello' function from the shared library
                    build()
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Call the 'deply' function from the shared library
                    deployDemo()
                }
            }
        }
    }
}
