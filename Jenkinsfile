pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'mvn package -Dhttps.protocols=TLSv1.2'
                bat 'move "C:\\Program Files (x86)\\Jenkins\\workspace\\My_Pipeline_master\\target\\Struts2HelloWorldExample.war" "C:\\Users\\klhua\\OneDrive\\Documents\\apache-tomcat-9.0.31\\webapps"'
            }
        }
    }
}
