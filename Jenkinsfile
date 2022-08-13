pipeline {
    agent { label 'hp' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "curl ifconfig.co"
            }
        }
    }
}
