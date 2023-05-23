pipeline {
    agent any

    stages {
         stage('1') {
            steps {
                echo 'Credenciales'
                git credentialsId: 'keyGithub', url: 'https://github.com/pesquerra/EjercicoSistemaNoticias.git'
            }
        }
         stage('2') {
           
            steps {
                echo 'commit'
                git commit -m "add archivo jenkins"
            }
        }
         stage('3') {
            steps {
                echo 'merge'
                git merge master -m "desde Jenkins"
            }
        }
    }
}
