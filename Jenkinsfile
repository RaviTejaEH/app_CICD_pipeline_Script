pipeline{
    tools {
        maven 'Maven-3.6.3'
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
