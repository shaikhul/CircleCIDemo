pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World!"'
                sh '''
                    whoami
                    pwd
                    date
                    uname -a
                '''
            }
        }
    }
}