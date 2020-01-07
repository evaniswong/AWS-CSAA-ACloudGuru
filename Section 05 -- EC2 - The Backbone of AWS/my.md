#### Exam Tips - Roles Lab
* Roles are more secure than storing your access key and secret access key on individual EC@ instances
* Roles are easier to manage
* Roles can be assigned to an EC2 instance AFTER it has been provisioned using both the command line and the AWS console
* Roles are universal - you can use them in any region

#### Exam Tips - Instance Metadata
* Used to get information about an instance (such as public IP)
* curl http://169.254.169.254/latest/meta-data
* curl http://169.254.169.254/latest/user-data

#### Exam Tips - EFS Lab
* Supports the Network File System version 4 (NFSv4) protocol
* You only pay for the storage you use (no pre-provisioning required)
* Can scale up to the petabytes
* Can support thousands of concurrent NFS connections
* Data is stored across multiple AZ's within a region
* Read After Write Consistency
