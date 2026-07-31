pipeline {
    agent any

    stages {

         stage('Build') {
            steps {
                echo "Building application from ${env.BRANCH_NAME} branch..."
            }
        }        }

    post {
        always {
            echo "Pipeline completed for ${env.BRANCH_NAME}"
        }
    }
}
