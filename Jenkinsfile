pipeline {
    agent any
    stages {
        stage('Clone sources') {
            steps {
                git url: 'git@github.com:vinaypremkumar/exec-java.git'
            }
        }
        stage('Checkout') {
            steps {
                git branch: 'master',  url: 'git@github.com:vinaypremkumar/exec-java.git'
            }
        } 
    }
}
    
