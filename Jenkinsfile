pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'chmod +x hello.sh'
            }
        }
        stage('Test') {
            steps {
                sh './hello.sh'
            }
        }
    }
}
