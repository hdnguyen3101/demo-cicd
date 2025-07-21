pipeline {
    agent { label 'ubuntu' }
    tools {
        nodejs 'nodejs-22.17.1'
        dockerTool 'docker'
    }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
