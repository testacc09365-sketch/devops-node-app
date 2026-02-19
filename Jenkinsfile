pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning Code...'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run App Check') {
            steps {
                sh 'node -v'
            }
        }
    }
}
