pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name dynamodbCFT --template-body file://dynamodbcft.json --region 'us-east-1'"
              }
             }
            }
            }