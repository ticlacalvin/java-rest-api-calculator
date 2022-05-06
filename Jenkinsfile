pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/ticlacalvin/java-rest-api-calculator.git'
                sh './mvnw clean compile'
            }
        }
    }
}
