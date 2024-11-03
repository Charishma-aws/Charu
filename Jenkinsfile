pipeline {
    agent any
    environment {
        course= "aws"
    }

    stages {
        stage('stage1') {
            environment {
                course= "devops"
            }
            steps {
                echo "my name is charishma, i am learning $course"
            }
        }
        stage('stage2') {
            steps {
                echo "my name is eshwar, iam leaning $course"
            }
    }
    }
}


