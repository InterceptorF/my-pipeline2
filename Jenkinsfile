pipeline {
    agent any
    options {
        datadog(collectLogs: true, tags: ["foo:bar", "bar:baz"])
    }
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
