pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Selam Dünyali"
            }
        }
        stage('test') {
            steps {
                echo "Selam Dünyali"
                sh 'echo using shell within Jenkinsfile'
            }
        }
        stage('deploy') {
            steps {
                echo "Selam Dünyali"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
    }
}