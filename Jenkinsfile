pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "/usr/local/bin/aws cloudformation create-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
              }
             }
            }
            }
