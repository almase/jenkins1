pipeline {
    agent any
    //Definir Variables
    environment {
        FICHERO = "/etc/group"
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
