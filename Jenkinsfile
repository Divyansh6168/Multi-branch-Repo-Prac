pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.master}"
            }
        }
	stage('Test') {
            steps {
                echo "Testing branch: ${env.master}"
            }
        }
	stage('Deploy') {
            steps {
                echo "DEploying branch: ${env.master}"
            }
        }
    }
    post {
        always {
            echo "Multi Branch job finished, done some changes!"
        }
    }
}


