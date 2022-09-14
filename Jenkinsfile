pipeline {
    agent any 
    stages {
        stage('PortTest') { 
            steps {
                sh 'sudo lsof -i:8000'
            }
        }
        stage('TokenTest') { 
            steps {
                echo 'Making the 8200 port Test'

            }
        }
    }
}
