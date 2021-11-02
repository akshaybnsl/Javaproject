pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World - Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World - Test'
            }
        }
            stage('Deploy') {
            steps {
                echo 'Hello World - Deploy'
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
            }
    }
            post {
                always {
                    echo 'I will always say Hello again!'
                }
            }
            

}
