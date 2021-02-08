pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                echo 'Testing'
            }
        }
        stage('check') {
            steps {
                echo 'Checking'
            }
        }
        stage('production') {
            steps {
                echo 'Production'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment'
            }
        }
    }
}
