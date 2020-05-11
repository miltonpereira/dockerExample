pipeline {
    agent { docker { image "dockerexample" } }
    stages {
        stage('build') {
            steps {
                sh 'docker build dockerexample'
            }
        }
    }
}