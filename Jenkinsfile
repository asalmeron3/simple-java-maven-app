pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps {
                withMaven(maven : 'maven_3_6_1') {
                    sh 'mvn -B -DskipTests clean package' 
                }
            }
        }
    }
}