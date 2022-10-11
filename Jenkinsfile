pipeline {
    agent {label 'MAVEN3 && NVM && PYTHON3'} 
    stages {
        stage('clone') { 
            steps {
                git url:'https://github.com/Sharmila-qt1/openmrs-core.git, branch : 'master' 
            }
        }
        stage('install') { 
            steps {
               sh 'java -version'
            }
        }
    }
}