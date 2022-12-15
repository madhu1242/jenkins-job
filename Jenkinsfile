pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hi World'
            }
        }
        stage('BUBU'){
            steps{
                echo 'iam madhuri'
            }
        }
    }
    post { 
        always { 
            echo 'Running after the stages'
        }
    }
}