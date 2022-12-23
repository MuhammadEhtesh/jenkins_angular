pipeline {
    agent any 

    stages() {
       stage('Clone'){
        steps {
            cleanWs()
            checkout scm
        }
       }
    }
}