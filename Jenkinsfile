pipeline {
    agent any

    stages {
        stage('Clonar repositorio') {
            steps {
                echo 'Código clonado automáticamente por Jenkins'
            }
        }

        stage('Listar archivos') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Ejecutar script Python') {
            steps {
                sh 'python3 script.py'
            }
        }
    }
}
