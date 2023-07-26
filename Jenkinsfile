pipeline {
    agent any
    tools {
        go 'ses' // 'ses' should match exactly with the name you've given to the Go version in Jenkins' Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                // Replace this with your build command
                sh 'go build .'
            }
        }
        stage('Test'){
            steps{
                // Replace this with your test command
                sh 'go test'
            }
        }
    }
}

