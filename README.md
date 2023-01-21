## CloudFormation-Simple-VPC
A Simple CloudFormation Template that Deploys: 
- VPC
- Internet Gateway
- Attached the IGW to the VPC
- 2 Public Subnets in AZ1 & AZ2
- Public Route Tables
- 4 Private Subnets in AZ1 & AZ2
    - 2 Private Subnets for App Tier
    - 2 Private Subnets for Data Tier
- 3 Security Groups
    - ALB Security Group
    - SSH Security Group
    - Web Server Security Group
    - Database Security Group
