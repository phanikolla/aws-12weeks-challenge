# Create a VPC

Our First step is to create a simple VPC using CloudFormation

1) Open a text editor and create an empty YAML File called sfid-cfn-vpc.yaml
2) Copy and paste the sample CloudFormation template below that defines a VPC and save the file.

Resources:
  # Create a VPC
  MainVPC:
    Type: AWS::EC2::VPC
    Properties:
      CidrBlock: 10.0.0.0/16