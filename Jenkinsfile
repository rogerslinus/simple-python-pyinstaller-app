/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.3-alpine3.21' } }
    stages {
        stage('build') {
            steps { 
                sh 'python --version'
                sh 'ls /var/jenkins_home/workspace/le-python-pyinstaller-app_master'
            }
        }
    }
}
