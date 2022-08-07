pipeline {
    agent any

    stages {

        stage('Deployment Intiated') {
            steps {
                echo 'Hello World'
            }
        }

        stage('stage started') {
            input {
                message "Are you sure? Shall I procced with deployment"
                ok "yes! Approved"
                submitter "preethi"
                parameters {
                    string(name: 'Approve/Reject', defaultValue: 'Ms. Preethi', description: 'deployment progress')
                }
            }
            steps {
                echo 'Deploment details'
            }

        stage('Deployment completed') {
            steps {
                echo 'Succesfully'
            }
        }
        }
    }
}
