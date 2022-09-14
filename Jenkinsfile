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
                sh 'sudo lsof -i:8086'

            }
        }
    }
}
