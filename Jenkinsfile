pipeline {
    agent any
    stages{
        stage('parallel-level'){
            parallel{
                stage('sub-job1'){
                    steps{
                        echo "sub-job1 task"
                    }
                }
                stage('sub-job2'){
                    steps{
                        echo "sub-job2 task"
                        echo "testing second demo"
                    }
                }
            }
        }
        stage('version-control'){
            steps{
                echo "end of parallel job"
            }
        }
    }
}
