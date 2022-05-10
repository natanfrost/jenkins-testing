pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo wtf'
            }
        }
        stage('Build more') {
            steps {
                sh '''
                    echo "multi wtf"
                    ls -lah
                '''
            }
        }
    }
}
