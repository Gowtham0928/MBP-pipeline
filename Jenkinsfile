pipeline {
    agent any

    tools {
        maven 'Maven 3.8.8'   // ✅ This name must match what is configured in Jenkins > Global Tool Configuration
    }

    stages {
        stage('Build with Maven') {
            steps {
                echo '🚀 Running Maven build...'
                sh 'mvn --version'
            }
        }
    }
}
