pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('stage one') {
            steps {
                echo 'Hello World'
            }
        }

        stage('stage two') {
            steps {
                echo ''
            }
        }

        stage('stage three') {
            input {
                message "Are you sure? Shall I procced with deployment"
                ok "yes you can procced"
                submitter "preethi"
                parameters {
                    string(name: 'preethi', defaultValue: 'Ms. Preethi', description: 'deployment progress')
                }
            }
            steps {
                echo 'cloud'
            }
        }
    }
}
