pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'test in first step'
            }
        }
    }
    post {
        always {
            sayHello 'Pravin'
        }
    }
}