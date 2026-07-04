pipeline {
    agent any

    stages {

        stage('Trigger Test Job') {
            steps {
                build job: 'testjob'
            }
        }

        stage('Trigger Prod Job') {
            steps {
                build job: 'prodjob'
            }
        }
    }
}    
