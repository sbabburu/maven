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
                sh 'mvn test'
                junit '**/target/surefire-reports/TEST-*.xml'
            }
        }
    }
}
