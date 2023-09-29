pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building triggered by webhooks... hopefully'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing triggered by webhooks...'
            }
        }
    }
}
