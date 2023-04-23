pipeline {
    agent any
    stages{
        stage('WORKING STAGE'){
            steps {
                
                bat 'xcopy /S "*" "C:/xampp/htdocs/exp4" /Y'
            }
        }

        stage('FINAL STAGE'){
            steps{
                echo 'Done!'
            }
        }
    }
}
