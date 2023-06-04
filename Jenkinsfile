pipeline {
    agent any
    
    stages {
        stage('Install MongoDB') {
            steps {
                sh ''
                sh ''
            }
        }
        
        stage('Install Dependencies - Server') {
            steps {
                dir('server') {
                    sh ''
                }
            }
        }
        
        stage('Run Server') {
            steps {
                dir('server') {
                    sh "ls"
                    sh ''
                }
            }
        }
        
        stage('Install Dependencies - Client') {
            steps {
                dir('client') {
                    sh ''
                }
            }
        }
        
        stage('Run Client') {
            steps {
                dir('client') {
                    sh ''
                }
            }
        }
    }
}
