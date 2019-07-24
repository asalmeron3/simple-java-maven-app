pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                withMaven(maven : 'maven361') {
                    sh 'mvn clean package' 
                }
            }
        }
    }
}