pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                branch 'feature'
            }             
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            when {
                branch 'test'
            }  
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
