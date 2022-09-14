pipeline {
    agent any 
    stages {
        stage('PortTest') { 
            steps {
                echo 'Making the 8200 port Test'
                
            }
        }
        stage('TokenTest') { 
            steps {
                sh 'sudo lsof -i:8000'

            }
        }
    }
}
