pipeline {
    agent {
        label 'agent-1'
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo this is build stage'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this is test stage'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is deploy stage'
            }
        }
    }
}
