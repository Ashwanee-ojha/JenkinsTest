pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out GitHub code'
            }
        }

        stage('Run JavaScript Test') {
            steps {
                echo 'Starting JavaScript test'
                bat 'node test.js'
            }
        }

        stage('Success') {
            steps {
                echo 'JavaScript test completed successfully'
            }
        }
    }
}
