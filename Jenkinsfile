pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello1234 World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
