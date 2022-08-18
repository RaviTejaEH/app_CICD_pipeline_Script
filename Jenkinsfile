pipeline{
    agent any
    stages{
        stage ('initialize') {
            steps{
                echo 'PATH = $PATH;' 
                echo 'M2_HOME= $M2_HOME'
            }
        stage ('build') {
            steps{
                sh 'mvn clean package'
            }
        }
        }
    }
}
