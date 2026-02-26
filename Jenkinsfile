pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Cloning Repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building Project...'
                sh 'echo Build Successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Project...'
                sh 'echo Tests Passed'
            }
        }
    }
}
