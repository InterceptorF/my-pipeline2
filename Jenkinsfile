pipeline {
    agent any

    stages {
        stage('Build') {
            steps { 
                echo 'python3 --version'
                echo 'Building..'
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
