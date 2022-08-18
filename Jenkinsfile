pipeline{
    tools {
        maven 'maven'
    }
    agent any
    stages{
        stage ('build') {
            steps{
                sh 'mvn clean package'
            }
        }
        }
    }
