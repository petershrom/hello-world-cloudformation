# hello-world-cloudformation

This is a test cloudformation template that sets up a Security Group and a Single app server from my pre-built AMI

It takes the following inputs

1. Keyname : Name of the EC2 Keypair for SSH access
2. SSHLocation : IP range to allow SSH access to the machine

It outputs the following

1. InstanceId : The instance ID of the EC2 instance
2. AZ : The availability zone the EC2 instance is in
3. PublicDNS : The public DNS name of the EC2 instance
4. PublicIP : The public IP of the EC2 instance
