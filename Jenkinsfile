pipeline{
    agent any
    tools {
        maven 'maven'
    }
    stages{
        stage ('initialize') {
            steps{
                echo "PATH = ${PATH}"
                echo 'executed 1st command'
                echo "M2_HOME = ${M2_HOME}"
                echo 'executed 2nd command' 
            }
        }
        stage ('Build') {
            steps{
                sh "mvn clean package"
            }
        }
    }
}
