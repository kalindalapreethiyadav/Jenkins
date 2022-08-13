pipeline {
    agent { label 'java'}

    stages {
        parallel {
        stage('Step 1 ') {
            steps {
                sh "curl ifconfig.co"
            }
        }

       stage('Step 2 ') {
            steps {
                echo 'Hello World'
         
            }
        }
     }
    }
}
