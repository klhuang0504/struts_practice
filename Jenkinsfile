pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
                bat 'mvn package -Dhttps.protocols=TLSv1.2'
            }
        }
    }
}
