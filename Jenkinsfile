pipeline {
    agent any

    stages {
        stage('Listar arquivos') {
            steps {
                echo 'Hello World...'
                sh('ls -l')
            }
        }
        stage(Maven Clean) {
            steps {
                echo 'Maven Clean...'
                sh('mvn clean')
            }
        }
    
    }
}