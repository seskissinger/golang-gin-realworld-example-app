pipeline {
    agent any

    tools {
        go 'go'
    }

    stages {
        stage('Build') {
            steps {
                sh 'go build -v ./...'
            }
        }
        stage('Test') {
            steps {
                sh 'go test -v ./...'
            }
        }
    }
}

