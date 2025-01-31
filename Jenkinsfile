pipeline {
    agent any  // This tells Jenkins to run on any available agent
 
    stages {
        stage('Test Connection') {
            steps {
                script {
                    echo "Jenkins pipeline is up and running!"
                    echo "The current branch is ${env.GIT_BRANCH}"
                    echo "The commit SHA is ${env.GIT_COMMIT}"
                    echo "Job running on: ${env.NODE_NAME}"
                }
            }
        }
    }
}
