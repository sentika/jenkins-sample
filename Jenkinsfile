pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'npm ci --no-optional'
            }
        }
    }
}
