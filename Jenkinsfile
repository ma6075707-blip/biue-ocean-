pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                timeout(time: 5, unit: 'SECONDS') {
                    echo 'Build Stage'
                }
            }
        }

        stage('Test') {
            steps {
                echo 'Test Stage'
            }
        }
    }
}