# AnsysChallenge

Interview Coding Challenge: Terraform Infrastructure as Code

Problem Statement:
You are tasked with writing terraform code to provision resources within AWS. Your goal is to create a Virtual Private Cloud (VPC) with both public and private subnets across multiple availability zones. Next provision an EC2 instance in which a hypothetical nginx running on port 80 will later be installed. You will need to ensure that this box is reachable over HTTP (port 80) by IP address.

Requirements:\
•Utilize Terraform to provision resources.\
•Create a VPC with CIDR block 10.0.0.0/16.\
•Create three public subnets across different availability zones within the VPC\
•Create three private subnets across different availability zones within the VPC\
•Ensure that instances in the public subnets have internet access, while instances in the private subnets do not have direct internet connectivity.\
•Parameterize your Terraform code appropriately for reusability and flexibility.\
•Ensure you have meaningful commit messages, so we can follow your thought process\
•Code should contain NO comments

Additional Information:\
•Assume you have the necessary AWS credentials configured for Terraform to access AWS services.\
•Feel free to make reasonable assumptions where details are not explicitly provided.\
•Do not leverage Terraform modules or existing community modules\
•We are looking for clean straightforward, minimal code that meets the problem statement and requirements

Future steps:\
• add remote_state.tf\
• folder structure for diff envs or use workspaces