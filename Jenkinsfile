pipeline {
    agent any 
    stages {
        stage('PortTest') { 
            steps {
                echo 'Making the 8200 port Test'
                sh 'sudo lsof -i:8000'
            }
        }
        stage('TokenTest') { 
            steps {
                sh 'sudo lsof -i:8086'

            }
        }
    }
}
