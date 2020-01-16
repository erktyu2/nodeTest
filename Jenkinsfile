pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "failure of node compiling"
                    ls -la
                    node testnodeProject.js
                    cd react/testreactapp/
                    npm run build
                '''
            }
        }
    }
}