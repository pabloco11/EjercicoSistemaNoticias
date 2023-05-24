pipeline {
    agent any

    stages {
        stage('1') {
            steps {              
                echo 'commit'
                sh 'git commit -am "Realizar cambios"'
                sh 'git push origin master'
            }
        }
         
    }
}
