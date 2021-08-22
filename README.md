# social-saver
Minimal sample project to accept HTTP requests to save social posts, 
save them to persistent storage, and allow retrieval.

#### Steps to get back to point where I left off 2 months ago:

* In WSL2 navigate to project directory
* Initiate virtual env
* Use pip to install dependencies
* Call CDK to deploy

```bash
cd ecs-devops-sandbox-cdk

source .venv/bin/activate

pip install -r ../requirements.txt

pip install aws_cdk.aws_ec2 aws_cdk.aws_ecs aws_cdk.aws_ecr aws_cdk.aws_iam

cdk deploy
```

Create  AWS CodeBuild Project



https://aws.amazon.com/blogs/containers/create-a-ci-cd-pipeline-for-amazon-ecs-with-github-actions-and-aws-codebuild-tests/

https://aws.amazon.com/premiumsupport/knowledge-center/ecs-fargate-static-elastic-ip-address/
