pipeline {
    agent { label 'standalone' }
    stages {
        stage('List files') {
            steps {
                sh "ls -l"
            }
        }
        stage('Test') {
            steps {
                echo "Success"
            }
        }
    }
}
