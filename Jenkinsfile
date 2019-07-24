pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                withMaven(maven : 'maven361') {
                    sh 'mvn -B -DskipTests clean package' 
                }
            }
        }
    }
}