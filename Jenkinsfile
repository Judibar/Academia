pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola hola"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola a tu mundo"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "hola wooop"
                '''
            }
        }
    }
}
