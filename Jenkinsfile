/*
pipeline {
    //small change

    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/EneAndrei01/java-rest-api-calculator'
                bat 'mvn clean compile'
            }
        }
        stage('Test') {
            steps{
                bat 'mvn test'
            }

            post{
                always {
                    junit '**//*
target/surefire-reports/TEST-*.xml'
                }
            }
        }
        stage('Publish'){
            steps{
                bat 'mvn package'
            }
            post{
                success{
                    archiveArtifacts 'target */
/*.jar'
                }
            }
        }
    }
}
 */
