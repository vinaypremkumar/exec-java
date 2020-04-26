pipeline {
    agent any
    stages {
        stage('Clone sources') {
            steps {
                git url: 'https://github.com/vinaypremkumar/exec-java.git'
            }
        }
        stage('Checkout') {
            steps {
                git branch: 'master',  url: 'https://github.com/vinaypremkumar/exec-java.git'
            }
        }
        stage('Maven Build') {
            steps {
                sh '/opt/maven/bin/mvn package'
                sh 'java -jar target/zilla-0.1-jar-with-dependencies.jar'
            }
        }    
    }
}
    
