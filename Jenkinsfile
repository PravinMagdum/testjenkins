pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'test in first step'
                script{
                new sayHello.call()
                }
            }
        }
    }
}