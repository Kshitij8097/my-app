pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
               bat "D:\\Java\\Maven\\apache-maven-3.6.0\\bin\\mvn.cmd clean"
            }
        }
        stage('Test') { 
            steps {
               bat "D:\\Java\\Maven\\apache-maven-3.6.0\\bin\\mvn.cmd test"
            }
        }
        stage('Deploy') { 
            steps {
               bat "D:\\Java\\Maven\\apache-maven-3.6.0\\bin\\mvn.cmd package" 
            }
        }
    }
}
