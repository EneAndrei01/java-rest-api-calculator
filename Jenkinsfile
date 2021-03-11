pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/EneAndrei01/java-rest-api-calculator'
                bat 'mvn clean compile'
            }
        }
    }
}
