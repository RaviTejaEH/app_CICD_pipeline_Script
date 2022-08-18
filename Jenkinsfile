pipeline{
    tools {
        maven 'Maven'
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
