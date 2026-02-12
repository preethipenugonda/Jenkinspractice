pipeline {
    agent any

    stages {
        stage('Hello Stage') {
            steps {
                echo 'Hello Gouthami! Jenkins pipeline is working 🎉'
                echo 'these is testing purpose'
                echo 'Hi i checking for commit event'
              '

        
            }
        }
        stage('Terraform') {
            steps {
                
                sh '''
                  terraform init
                  terraform plan
                '''

            }
        }
    }
}
