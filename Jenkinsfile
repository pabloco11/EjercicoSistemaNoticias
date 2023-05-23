pipeline {
    agent any

    stages {
         stage('Hello') {
            steps {
                echo 'Credenciales'
                git credentialsId: 'keyGithub', url: 'https://github.com/pesquerra/EjercicoSistemaNoticias.git'
            }
            steps {
                echo 'commit'
                git commit -m "add archivo jenkins"
            }
            steps {
                echo 'merge'
                git merge master -m "desde Jenkins"
            }
        }
    }
}
