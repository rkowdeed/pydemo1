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
        stage('Run') {
            steps {
                bat 'python demo4.py'
            }
        }
    }
}