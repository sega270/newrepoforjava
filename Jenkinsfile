pipeline {
    agent any

    stages {
        stage('Checout') {
            steps {
                echo git 'https://github.com/sega270/newrepoforjava.git'
            }
        }
    
        stage('Build') {
            steps {
                echo 'Compiling in progress'
                bat 'javac New.java'
                
            }
        }
        stage('Execute') {
            steps {
                echo 'Testing in progress'
                bat'java New'
            }
        }
      
    }
}

