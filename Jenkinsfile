pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello12345 World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
