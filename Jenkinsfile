pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Im Fine'
            }
        }
        stage('Environment') {
            steps {
                echo env.JOB_NAME
                echo env.BUILD_ID
            }
        }
    }
}
