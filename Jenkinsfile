pipeline {
    agent any

    stages {
        stage('Hello Stage') {
            steps {
                echo "Hello Gouthami Jenkins pipeline is working"
                echo "This is testing purpose"
                echo "Hi I am checking for commit event"
            }
        }

        stage('Terraform') {
            steps {
                sh """
                echo Hello
                echo Jenkins
                """
            }
        }
    }
}
