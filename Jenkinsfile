pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello123 World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
