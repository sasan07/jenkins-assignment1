pipeline {
    agent any

    stages {

        stage('Trigger Test Job') {
            steps {
                build job: 'Push-to-Test'
            }
        }

        stage('Trigger Prod Job') {
            steps {
                build job: 'Push-to-Prod'
            }
        }
    }
}    
