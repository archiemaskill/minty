pipeline {
    //agent { docker { image 'maven:3.3.3' } }
    agent any
    stages {
        stage('build') {
            steps {
                sh './mvnw package'
            }
        }
        stage('test') {
            steps {
                sh './mvnw test'
            }
        }
    }
}