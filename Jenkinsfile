pipeline {
    agent any

    stages {
        stage('1') {
            steps {
                echo 'Credenciales'
                git credentialsId: 'keyGithub', url: 'https://github.com/pesquerra/EjercicoSistemaNoticias.git'
                echo 'commit'
                git commit -m "add archivo jenkins"
                echo 'merge'
                git merge master -m "desde Jenkins"
            }
        }
         
    }
}
