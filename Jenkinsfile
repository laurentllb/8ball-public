Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Simple pipeline'
                sh 'mvn --version'
            }
        }
    }
}
