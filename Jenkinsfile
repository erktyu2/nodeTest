pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "npm install, test jest"
                    npm install
                    npm run test
                '''
            }
        }
    }
}