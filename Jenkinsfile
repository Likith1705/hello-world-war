pipeline {
    agent any

    stages {
        stage('Check out') {
            steps {
                sh "git clone https://github.com/Likith1705/hello-world-war.git"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
