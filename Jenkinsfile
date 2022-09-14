pipeline {
    agent any 
    stages {
        stage('PortTest') { 
            steps {
                echo 'Making the 8283 port Test'
                sh 'sudo lsof -i:8083'
            }
        }
        stage('TokenTest') { 
            steps {
                sh 'sudo lsof -i:8086'

            }
        }
    }
}
