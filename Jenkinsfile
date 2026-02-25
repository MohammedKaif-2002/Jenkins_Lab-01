pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Checking branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Run Program') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
