pipeline {
    agent any

    parameters {
        string(name: 'ENV', defaultValue: 'DEV')
    }

    stages {
        stage('Show Env') {
            steps {
                echo "Environment: ${params.ENV}"
            }
        }
    }
}
