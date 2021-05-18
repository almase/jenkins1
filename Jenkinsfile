pipeline {
    agent any
    //Definir Variables
    environment {
        FICHERO = "/etc/passwd"
    }
    stages {
        stage('Fecha') {                    
            steps {
                sh 'date'
            }
        }
        stage('ContarUsuarios'){
            steps{
                sh 'wc -l ${FICHERO}'
            }
        }
    }
}
