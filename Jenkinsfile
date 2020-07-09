pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "helloworld"
                node index.js
                sh 'sleep 10'
            }
        }
    }
}
