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
                ok "yes! Approved"
                submitter "preethi"
                parameters {
                    string(name: 'Approve/Reject', defaultValue: 'Ms. Preethi', description: 'deployment progress')
                }
            }
            steps {
                echo 'cloud'
            }
        }
    }
}
