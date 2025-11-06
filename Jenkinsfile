pipeline {
    agent any 
    environment {
        envi ='pre-prd'
    }
    stages {
        stage('pre') {
            when {
                environment name: 'envi', value: 'pre-prod'
            }
            steps {
                echo  "when its is succsful"
            }
        }
        stage('dev'){
               steps{
                   echo "done"
               }
        }
    }
}
