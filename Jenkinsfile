pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                echo 'Start..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cat test1-file'
                echo 'Deploy..'
            }
        }
        stage('End') {
            steps {
                echo 'End....'
            }
        }
    }
}
