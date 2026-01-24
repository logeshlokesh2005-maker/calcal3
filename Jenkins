pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/logeshlokesh2005-maker/calcal3.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building your project...'
                // Add your build commands here (e.g., sh 'make' or sh './gradlew build')
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }
    }
}
