pipeline {
agent any 
  stages {
    stage('Build EKS Cluster and Nodegroup') {
      steps {
        sh "aws cloudformation create-stack --stack-name ranveerEKS --template-body file://eks.yaml --region 'us-east-1'"
      }
    }
  }

}
