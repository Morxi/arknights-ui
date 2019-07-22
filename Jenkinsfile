
Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php -S'
            }
        }
    }
}

