pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building stage...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing stage...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying stage...'
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed'
        }
        success {
            echo 'Build was successful 🎉'
        }
        failure {
            echo 'Build failed ❌'
        }
    }
}
