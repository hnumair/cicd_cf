pipeline{
	agent any
	stages {
		stage('Submit Stack') {
			steps {
			sh "aws cloudformation create-stack --stack-name jenkinsStack --template-body file://samtemplate.yaml --region 'ap-south-1'"
			}
		}
	}
}
