pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
      stage('git_version') {
            steps {
                sh 'git version'
            }
        }
        stage('docker_version') {
            steps {
                sh 'docker --version'
            }
        }
        stage('sleep_30') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('pollingEveryHr') {
            steps {
                sh 'date'
            }
        }
    }
}
