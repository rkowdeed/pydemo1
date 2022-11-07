pipeline {
    agent any

    stages {
// some comment
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python demo4.py'
            }
        }
    }
}