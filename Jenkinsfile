pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2sg --template-body file://ec2sg.yaml --region 'us-east-1'"
              }
             }
            }
            }
