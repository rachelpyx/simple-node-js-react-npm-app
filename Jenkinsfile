    agent any
    stages {
        stage('Build') {
            steps {
                nodejs('nodejs'){
                        sh 'npm install'
                }
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }