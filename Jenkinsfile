pipeline {
    agent {label 'MAVEN3 && NVM && PYTHON3'} 
    stages {
        stage('clone') { 
            steps {
                git url:'https://github.com/Sharmila-qt1/gameoflife.git, branch : 'master' 
            }
        }
        stage('install') { 
            steps {
               sh 'clean install'
            }
        }
    }
}