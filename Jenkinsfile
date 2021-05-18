pipeline {
    agent any

    stages {
        stage('Fecha') {
            steps {
                sh 'date'
            }
        }
        stage('ContarUsuarios'){
            steps{
                sh 'wc -l /etc/passwd'
            }
        }
    }
}
