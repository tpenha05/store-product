pipeline {
    agent any
    tools {
        maven 'maven-3'
        jdk 'jdk-21'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean install'
            }
        }
    }

}