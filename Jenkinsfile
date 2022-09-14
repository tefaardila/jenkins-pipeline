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
                sh ' curl -X POST  http://127.0.0.1:8000/login -d \'{"username": "admin","password": "admin"}\''

            }
        }
    }
}
