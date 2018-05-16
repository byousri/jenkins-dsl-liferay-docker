pipeline {
    agent {
        docker { image 'byousri/liferay:7.0.3-ga4-tomcat' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'java --version'
            }
        }
    }
}