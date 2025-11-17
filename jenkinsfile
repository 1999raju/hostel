pipeline {
    agent any

    stages {

        stage('clone') {
            steps {
                echo "Repository cloned by Jenkins automatically"
            }
        }

        stage('list the files') {
            steps {
                sh 'ls'
            }
        }

        stage('sleep') {
            steps {
                sleep time: 5, unit: 'SECONDS'
            }
        }

        stage('run') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
