$ python3 -m venv .venv

$ source .venv/bin/activate

$ pip install -r requirements.txt

$ cdk synth

$ export CDK_TARGET_ACCOUNT='12-digit-account-number'

$ export CDK_TARGET_REGION='ap-southeast-1'

setup aws credential profile for the target AWS acount

$ aws configure --profile cdk-target-profile

To setup CDK provisioned resources in your account, CDK Bootstrap is required.

$ cdk bootstrap --profile cdk-target-profile

$ cdk deploy --profile cdk-target-profile

*************************************** source at : 
/Users/fjabbari/REPO_CDK_AND_CDK8s_FREDv3/aws-cdk-python-example/cdk-eks-redis-bastion
(.venv) ╭─fjabbari@Freds-MacBook-Pro ~/REPO_CDK_AND_CDK8s_FREDv3/aws-cdk-python-example/cdk-eks-redis-bastion ‹main●› 
╰─$ 
***************************************
