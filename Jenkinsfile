pipeline {
    agent any
    tools{maven 'Maven'}
    stages {
        stage('build') {
            steps {
                echo 'build'
                sh 'mvn clean package'
            }}
}}
