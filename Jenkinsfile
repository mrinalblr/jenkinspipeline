pipeline {
    agent any

    stages {
        stage('Init'){
            echo 'Initializing the pipeline...'
        }
        stage('Build') {
            steps {
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
        stage('PostDeploy'){
            steps{
                echo 'Post deploy testing ....'
                echo 'Completed.'
            }
        }
    }
}