pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('BUBU'){
            steps{
                echo 'iam madhurima'
            }
        }
    }
    post { 
        always { 
            echo 'Running after the stages'
        }
    }
}