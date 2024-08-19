pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                bat 'git clone https://github.com/gudlaroshini/devops'
                bat '''mkdir C:\\ProgramData\\Jenkins\\hello.txt
'''
            }
        }
        stage('Hello1') {
            steps {
                echo 'Hello World1'
            }
        }
        stage('Hello2') {
            steps {
                echo 'Hello World2'
            }
        }
    }
}
