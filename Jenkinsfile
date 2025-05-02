Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.3-alpine3.21' } }
    stages {
        stage('build') {
            steps { withCredentials([usernamePassword(credentialsId: 'a04ab8c9-6cfd-4976-b0cd-c76fe67d9978', usernameVariable: 'USER', passwordVariable: 'PASSWORD')])
                sh 'python --version'
            }
        }
    }
}
