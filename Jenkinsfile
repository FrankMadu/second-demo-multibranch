pipeline {
    agent any
    stages{
        stage('Main Branch Deploy Code'){
            when{
                branch 'main'
            }
            steps {
                sh 'echo "Building Artifact from Main Branch"'
                sh 'echo "Deploying Code from Main Branch"'
            }
        }
        stage('Develop Branch Deploy Code'){
             when{
                branch 'develop'
            }
            steps {
                sh 'echo "Building Artifact from Develop Branch"'
                sh 'echo "Deploying Code from Develop Branch"'
            }
        }
    }
}

