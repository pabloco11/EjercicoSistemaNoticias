pipeline {
    agent any

    stages {
        stage('1') {
            steps {
                echo 'Credenciales'
                git credentialsId: 'keyGithub', url: 'https://github.com/pesquerra/EjercicoSistemaNoticias.git'
            }
        }
        
    }
}
