pipeline {
    agent { label 'ws' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "curl ifconfig.co"
            }
        }
    }
}
