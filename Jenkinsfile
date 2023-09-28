pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building triggered by webhooks...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing triggered by webhooks...'
            }
        }
    }
}
