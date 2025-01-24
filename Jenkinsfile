pipeline {
    agent any

    stages {
        stage('One') {
            steps {
                echo 'Hi, this is Snaatak Team'
            }
        }

        stage('Two') {
            steps {
                input('Do you want to proceed?')
            }
        }

        stage('Three') {
            when {
                branch "main"
            }
            steps {
                echo "Hello Ninja-batch-29 !!"
            }
        }

        stage('Four') {
            when {
                branch "prod"
            }
            steps {
                echo "hello opstree"
            }
        }
    }
}
