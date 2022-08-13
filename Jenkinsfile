pipeline {
    agent { label 'java'}

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "curl ifconfig.co"
            }
        }
    }
}
