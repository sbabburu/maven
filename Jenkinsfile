pipeline {
    agent any
    tools {
        maven 'maven 3.3.3' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn --version'
                sh 'mvn clean package'
            }
        }
    }
}
