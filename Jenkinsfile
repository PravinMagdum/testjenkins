pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'test in first step'
                script{
                sayHello.call()
                }
            }
        }
    }
}