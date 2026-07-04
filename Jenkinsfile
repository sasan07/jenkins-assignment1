pipeline {
    agent any
  
    stages {
        
        stage('Trigger test job')
            steps {
                build job: 'Push-to-test'
            }

        }
    stages {


        stage('Trigger prod job')
            steps {
                build job: 'Pust-to-prod'
            }
        }
   }
