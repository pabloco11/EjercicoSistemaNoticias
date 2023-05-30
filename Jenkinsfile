pipeline {
    agent any

    stages {
       
            stage('SonarQube analysis') {
    steps {
        withSonarQubeEnv('SonarQube') {
            sh 'mvn sonar:sonar' 
        }
        }
         
    }
}
