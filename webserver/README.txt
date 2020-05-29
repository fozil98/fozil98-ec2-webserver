
#Steps Taken for this project#

- Created a new VPC with 2 public AZ's

- New SG,RT,NACL,IGW

- EC2 instance

- S3 private bucket

- IAMRole to EC2 ( Access to S3 )

- SSH into EC2 to move zip to ec2

- unzip files and started webserver service

- Created AMI of the EC2

- Used the newly created AMI to launch a new EC2 in the second AZ.

- Created a Autoscaling Group of 2 Instances Accross the 2 public AZ

- Created a Application Load Balancer.