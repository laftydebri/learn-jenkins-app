pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'echo "Hello  from jenkins"'
                sh 'whoami'
                sh 'mkdir test'
            }
        }
    }
}