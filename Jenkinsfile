pipeline {
    agent any 
    stages {
        stage('print'){
            steps{
                sh "python ./main_test.py"
            }

        }
        stage('name'){
            steps{
                echo"karthi"
            }
        }
    }
}