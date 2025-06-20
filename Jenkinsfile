pipeline {
    agent any 
    stages {
        stage('dev envirnment') {
            when{
                not {
                branch 'main'
            }
            
        steps {
             echo "run in maqin branch"
        }
        }
    }
 }
