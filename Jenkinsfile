pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Kod indiriliyor...'
            }
        }

        stage('Build') {
            steps {
                echo 'Build aşaması çalıştı'
            }
        }

        stage('Test') {
            steps {
                echo 'Test aşaması çalıştı'
            }
        }
    }

    post {
        success {
            echo 'Pipeline SUCCESS 🎉'
        }
        failure {
            echo 'Pipeline FAILED ❌'
        }
    }
}
