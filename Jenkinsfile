pipeline {
    agent any

    tools {
        maven 'Maven 3.9.6'   // ✅ This name must match what is configured in Jenkins > Global Tool Configuration
    }

    stages {
        stage('Build with Maven') {
            steps {
                echo '🚀 Running Maven build...'
                sh 'mvn --version'
                sh 'mvn clean install'
            }
        }
    }
}
