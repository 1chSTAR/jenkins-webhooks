pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building triggered by webhooks... hopefully2'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing triggered by webhooks...hopefully2'
            }
        }
    }
}
