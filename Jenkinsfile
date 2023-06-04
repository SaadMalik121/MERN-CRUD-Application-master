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
                    sh 'npm install'
                }
            }
        }
        
        stage('Run Server') {
            steps {
                dir('server') {
                    sh 'node app.js'
                }
            }
        }
        
        stage('Install Dependencies - Client') {
            steps {
                dir('client') {
                    sh 'npm install'
                }
            }
        }
        
        stage('Run Client') {
            steps {
                dir('client') {
                    sh 'npm start'
                }
            }
        }
    }
}
