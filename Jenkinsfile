pipeline {

    agent any
    stages {

        stage("Build & Deploy SNAPSHOT") {
            steps {
                sh "mvn clean install"
            }
        }
