pipeline{
    tools {
        maven 'Maven'
    }
    agent any
    stages{
        stage ('initialize') {
            steps{
                sh ...
                        echo 'PATH = $PATH'
                        echo 'M2_HOME= $M2_HOME'
                   ...
            }
        stage ('building') {
            steps{
                sh 'mvn clean package'
            }
        }
        }
    }
}
