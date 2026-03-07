pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                 git branch:'master', url:'https://github.com/sega270/newrepoforjava.git'
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


