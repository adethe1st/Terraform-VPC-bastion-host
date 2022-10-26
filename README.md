# Terraform-VPC-bastion-host
Builds on top of the VPC 3 tier architecture to add a Bastion Host in one of the public subnets. An additional module is used in building the Bastion host, which is basically an EC2 instance.

Terraform provisioners are used in building these resources. A reference is made to an article on <a href="https://jhooq.com/terraform-provisioner/">Terraform provisioners.</a> 

Provisioners are used by terraform to define scripts and code that should be run once the resources are provisioned. They somewhat act as bootstrap data to run on the local or remote machines. An example would be defining environment variables aan copying filles from your local machine to the remote machine.

