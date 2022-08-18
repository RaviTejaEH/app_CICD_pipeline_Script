pipeline{
    tools {
        maven 'mvn'
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
