# AWS Cloud Practitioner Essentials

# Security
####Shared repsonsibility model
Stack divided up

Reponsibility AWS:
(We have no visibility of this)
- Physical
- Network
- Hypervisor

Responsibiity us:
(AWS has no visibility of this)
- Guest OS
- Application
- User Data

#### Permissions
Identity and Access Managment (IAM)

User - Permenant named operator human/machine (credentials permenant)
Group - Collection of users
Role - Not permisions, an AUTHENTICATION method, an operator. Credentials are temporary.

Everything in AWS an API need to authenticate and autherise (permissions)

Permisions happen in policy documnet (JSON) attaches to user, group, or role. Gives list of APIs allowed against which resources and conditions. 

API called (eg put object in s3) with credentials IAM engine then checks credentials, are these active and relating to user/group/role. If approved (you are the operator you say) Look at all policy docs is it autherised. 

EG can set policy to deny termination of instances in production unless autherised admin.

Cloud trail tracks all successful and unsucessful API calls and by who

#### Amazon Inspector
Security vulnerabiliites
automated service
access vulnerabilities and strays from security best practice

#### Amazon Sheild
Managed DDoS protection service
always on detectio and mitigations

# OVERVIEWS

#### EC2
elestic compute cloud
an instance is a server

##### Setting up an instance
Select region
EC2 launch instance
Select AMI
Select Hardwate 
Tags give easier identifier eg Key -name value-something easier

SSHing in 


