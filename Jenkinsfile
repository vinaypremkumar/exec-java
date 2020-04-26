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
    }
}
    
