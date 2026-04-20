pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Kuvar2708/satguruz.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
