pipeline {
    agent any

    stages {
        stage('Check out') {
            steps {
                sh "pwd"
                sh "rm -rf hello-world-war"
               // sh "git clone https://github.com/Likith1705/hello-world-war.git"
            }
        }
        stage('Build') {
            steps {
                sh "ls"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
